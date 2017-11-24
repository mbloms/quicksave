pkgname=quicksave
pkgver=1.1
pkgrel=1
pkgdesc='Save before doing something stupid'
arch=('any')
license=('Unlicense')
depends=('btrfs-progs'
		 'rsync')
url="https://github.com/mbloms/quicksave"
source=('quicksave'
	'LICENSE')
md5sums=('ed657529bc6e65959d9aa0c7cf4756cf'
         'd88e9e08385d2a17052dac348bde4bc1')

package() {
	install -Dm755 $pkgname "$pkgdir/usr/bin/$pkgname"
}
