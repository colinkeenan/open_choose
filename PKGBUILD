# Maintainer: Colin Keenan <colinnkeenan at gmail dot com>

pkgname=open_choose
pkgver=1.0
pkgrel=1
pkgdesc="'catfish --wrapper open_choose' for open-with dialog when open file in catfish"
arch=('any')
url="https://github.com/colinkeenan/open_with"
license=('GPL')
depends=('zenity' 'perl-file-mimeinfo')
install=${pkgname}.install

source=('open_choose')
md5sums=('2422db121230fb8f281a27ed5e4dd34d')

package() {
  install -d -m755 "$pkgdir/usr/bin"
  install -m755 open_choose "$pkgdir/usr/bin/gmv"
}