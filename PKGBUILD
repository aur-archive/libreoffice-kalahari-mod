# Maintainer: Stefano Bergamini

pkgname=libreoffice-kalahari-mod
pkgver=0.4.0.b
pkgrel=1
pkgdesc="Icons pack for libreoffice inspired by Kalahari icons"
arch=(any)
url="http://gnome-look.org/content/show.php/Faenza+Icons++for+LibreOffice++4.0.0?content=157970"
license=('GPL')
depends=('libreoffice-common')
conflicts=('libreoffice-human-mod' 'libreoffice-faenza-mod')
install=${pkgname}.install
source=('https://dl.dropboxusercontent.com/u/228553/images_human.zip')
noextract=('images_human.zip')
md5sums=('98339b4f7718275772a75cdfdcb707a1') 
_lo_dir=/usr/lib/libreoffice/share/config

package() {
mv images_human.zip images_kalahari.zip
mkdir -p $pkgdir$_lo_dir
cp images_kalahari.zip $pkgdir$_lo_dir

}
