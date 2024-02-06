# Maintainer: Tyrone Watermelon <tyronewatermlon@tutanota.com>
pkgname=watermelonos-scripts
pkgver=1
pkgrel=1
pkgdesc="Scripts for watermelonOS."
arch=('x86_64')
url="https://github.com/TyroneWatermelon420/watermelonos-scripts.git"
license=('MIT')
groups=()
depends=()
makedepends=(make)
checkdepends=()
optdepends=()
provides=(dwm)
conflicts=(dwm)
replaces=()
backup=()
options=()
source=("git+$url")
noextract=()
md5sums=('SKIP')
validpgpkeys=()

prepare() {
	cd $srcdir/${pkgname}
	# skip terminfo which conflicts with ncurses
	sed -i '/tic /d' Makefile
}

package() {
  cd "${pkgname}"  
}

