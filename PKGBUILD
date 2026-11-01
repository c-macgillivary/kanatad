pkgname=kanatad
pkgver=1.2
pkgrel=1

arch=('any')
depends=('kanata-bin' 'bash' 'systemd')

source=('kanatad@.service')
sha256sums=('SKIP')

package()
{
  install -Dm644 "$srcdir/kanatad@.service" "$pkgdir/usr/lib/systemd/system/kanatad@.service"
}
