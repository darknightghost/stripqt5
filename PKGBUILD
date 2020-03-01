# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=stripqt5
pkgver=0.1
pkgrel=1
pkgdesc="Pacman hook to strip qt5 libraries to solve problem that the applications using qt5 cannot run in WSL."
arch=('any')
url="https://github.com/darknightghost/stripqt5"
license=('GPL3')
depends=('pacman>=5.0.0' 'binutils')
changelog=
source=('stripqt5.hook')
noextract=('stripqt5.hook')
md5sums=('a94ec5188dd7330493260ed88f675047')

package() {
	mkdir -p "$pkgdir/usr/share/libalpm/hooks"
	cp "stripqt5.hook" "$pkgdir/usr/share/libalpm/hooks"

}
