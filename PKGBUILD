pkgname=2gis-yakutsk
pkgver=35
pkgrel=1
pkgdesc="Map of Yakutsk for 2GIS, July 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/yakutsk/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Yakutsk-35.orig.zip")
md5sums=('84b1ce567a89bad3c5432680901dde83')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Yakutsk.dgdat" "${pkgdir}/opt/2gis/2gis-yakutsk.dgdat" || return 1
  
}
