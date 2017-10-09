pkgname=quicksave
pkgver=1.0
pkgrel=1
pkgdesc='Save before doing something stupid'
arch=('any')
license=('Unlicense')
depends=('btrfs-progs'
		 'rsync')
url="https://github.com/mbloms/quicksave"
source=("https://github.com/mbloms/quicksave/archive/v1.0.tar.gz"
		'LICENSE')
md5sums=('9dfd333ce421524d8e9fdb9043dc424f'
         'd88e9e08385d2a17052dac348bde4bc1')

package() {
	cd "$pkgname-$pkgver"
	install -Dm755 $pkgname "$pkgdir/usr/bin/$pkgname"
}
