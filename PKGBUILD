pkgname=ibus-mozc-bin
pkgver=2.31.5851.102
pkgrel=1
arch=('any')
package(){
	git clone https://github.com/roistaff/ibus-mozc-bin.git
	cd ibus-mozc-bin/lib/
	sudo pacman -U mozc-2.31.5851.102-1-x86_64.pkg.tar.zst
	sudo pacman -U ibus-mozc-2.31.5851.102-1-x86_64.pkg.tar.zst
}
