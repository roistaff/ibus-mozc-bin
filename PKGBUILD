pkgname=ibus-mozc-bin
pkgver=2.31.5851.102
pkgrel=1
arch=('x86_64')
license=()
depends=('ibus')
provides=('ibus-mozc')
conflicts=('ibus-mozc')
source=("https://rawgithubusercontent.com/roistaff/ibus-mozc-bin/master/mozc-${pkgver}-1-x86_64.pkg.tar.zst",
	"https://rawgithubusercontent.com/roistaff/ibus-mozc-bin/master/ibus-mozc-${pkgver}-1-x86_64.pkg.tar.zst")
noextract=("ibus-mozc-${pkgver}-1-x86_64.pkg.tar.zst",
	"mozc-${pkgver}-1-x86_64.pkg.tar.zst")
package() {
  bsdtar -xf "mozc-${pkgver}-1-x86_64.pkg.tar.zst" -C "${pkgdir}"
  bsdtar -xf "ibus-mozc-${pkgver}-1-x86_64.pkg.tar.zst" -C "${pkgdir}"
}
