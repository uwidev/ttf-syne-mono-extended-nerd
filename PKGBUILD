pkgname=ttf-syne-mono-extended-nerd
pkgver=1.0.1
pkgrel=1
pkgdesc="Syne monospace extended, patched with nerd"
arch=('any')
license=('OFL')
source=("https://github.com/uwidev/$pkgname/raw/refs/heads/main/SyneMonoExtendedNerdFont-Regular.ttf")
sha256sums=("d0ccd0b8d5858c202f4e54d2b3d3d31146a89530571f42482921a8e2b4d62b68")

package() {
	install -dm 755 "$pkgdir"/usr/share/fonts/TTF
	install -Dm644 ./*.ttf "$pkgdir"/usr/share/fonts/TTF
}
