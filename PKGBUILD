pkgname=quicksave
pkgver=2.2
pkgrel=1
pkgdesc='Save before doing something stupid'
arch=('any')
license=('BSD')
depends=('btrfs-progs'
         'rsync'
         'pv'
         'fish')
url="https://github.com/mbloms/quicksave"
source=('quicksave'
	'LICENSE')
md5sums=('fd15782dd2b0bdc8a70c569d73285eb3'
         'd88e9e08385d2a17052dac348bde4bc1')

package() {
  install -Dm755 $pkgname "${pkgdir}/usr/bin/${pkgname}"
  install -Dm755 $pkgname "${pkgdir}/usr/bin/send"
  install -Dm444 LICENSE "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
