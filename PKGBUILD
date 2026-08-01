pkgname=kanata-daemon
pkgver=1.1
pkgrel=1

arch=('any')
depends=('kanata-bin' 'bash' 'systemd')

source=('kanata-daemon@.service')
sha256sums=('SKIP')

package()
{
  install -Dm644 "$srcdir/kanata-daemon@.service" "$pkgdir/usr/lib/systemd/system/kanata-daemon@.service"
}
