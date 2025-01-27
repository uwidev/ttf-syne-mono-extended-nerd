pkgname=ttf-syne-mono-extended-nerd
pkgver=1.0.0
pkgrel=1
pkgdesc="Syne monospace extended, patched with nerd"
arch=('any')
license=('OFL')
source=("https://github.com/uwidev/$pkgname/raw/refs/heads/main/SyneMonoExtendedNerdFont-Regular.ttf")
sha256sums=("0537eb3f3b3bc5d3e49d27d25a0cafb71353079bb7c1c2718a46a6cdb8e24966")

package() {
	install -dm 755 "$pkgdir"/usr/share/fonts/TTF
	install -Dm644 ./*.ttf "$pkgdir"/usr/share/fonts/TTF
}
