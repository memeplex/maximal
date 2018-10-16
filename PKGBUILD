# Maintainer: Carlos Pita <carlosjosepita@gmail.com>

pkgname=maximal
pkgver=20180705
pkgrel=2
pkgdesc='Hides the titlebar when a window is maximized in Gnome/Cinnamon'
arch=('any')
url='https://github.com/memeplex/maximal'
depends=('python-xlib')
makedepends=('git')
source=("maximal-git::git+$url.git")
md5sums=('SKIP')

package() {
    install -D $srcdir/maximal-git/maximal $pkgdir/usr/bin/maximal
}
