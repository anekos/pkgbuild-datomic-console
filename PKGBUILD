# Maintainer: anekos <anekos@snca.net>
pkgname=datomic-console
pkgver=0.1.214
pkgrel=1
pkgdesc="GUI console for datomic"
arch=('i686' 'x86_64')
url="http://datomic.com/"
depends=('glibc')
makedepends=('zip')
source=("datomic-console-${pkgver}.zip")
md5sums=('SKIP')

build() {
  echo building
}

package() {
  cd "$srcdir/$pkgname-$pkgver"
  mkdir -p "$pkgdir/usr/lib/datomic"
  bin/install-console "$pkgdir/usr/lib/datomic"
}

# vim:set ts=2 sw=2 et:
