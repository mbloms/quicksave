pkgname=quicksave
pkgver=1.3
pkgrel=1
pkgdesc='Save before doing something stupid'
arch=('any')
license=('Unlicense')
depends=('btrfs-progs'
         'rsync'
         'fish')
url="https://github.com/mbloms/quicksave"
source=('quicksave'
	'LICENSE')
md5sums=('b9ae91d2591689b7abb09072f1c0c548'
         'd88e9e08385d2a17052dac348bde4bc1')

package() {
  install -Dm755 $pkgname "${pkgdir}/usr/bin/${pkgname}"
  install -Dm444 LICENSE "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
