# Maintainer: wangsiyuan <darknightghost.cn@gmail.com>
pkgname=stripqt5
pkgver=0.1
pkgrel=1
pkgdesc="Pacman hook to strip qt5 libraries to solve problem that the applications using qt5 cannot run in WSL."
arch=('any')
install=$pkgname.install
url="https://github.com/darknightghost/stripqt5"
license=('GPL3')
depends=('pacman>=5.0.0' 'binutils')
changelog=
source=('stripqt5.hook' 'stripqt5.install')
noextract=('stripqt5.hook')
md5sums=('a94ec5188dd7330493260ed88f675047'
         '390f6649755e08826890ab39f5140a0e')

package() {
	mkdir -p "$pkgdir/usr/share/libalpm/hooks"
	cp "stripqt5.hook" "$pkgdir/usr/share/libalpm/hooks"

}
