
pkgname=youtube-dl-applet
pkgver=1.5
pkgrel=1
pkgdesc="This tool is convenient link handler, passing them to youtube-dl."
arch=('x86_64')
url='http://kde-apps.org/content/show.php/YouTube+DL+Applet?content=162896'
license=('GPL')
depends=('youtube-dl')
install=${pkgname}.install
source=("http://opendesktop.org/CONTENT/content-files/162896-${pkgname}-${pkgver}.tar.lzma")
sha512sums=('e2174f7c6cc9f0a25ef451bfffb74ed3065017ef53ed03925c5056170a6eabee873e6d25d5f93a64528db4da3623f2d84dc7b4665e92a342c1e0a83c054b6acb')

package() {
cd ${srcdir}/${pkgname}
  install -Dm755 $pkgname $pkgdir/usr/bin/$pkgname 
  install -Dm644 $pkgname.desktop $pkgdir/usr/share/applications/$pkgname.desktop
}
