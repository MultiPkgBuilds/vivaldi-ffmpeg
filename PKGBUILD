pkgname=vivaldi-ffmpeg
pkgver=51.0.2704.103
pkgrel=1
pkgdesc='Additional support for proprietary codecs for vivaldi.'
arch=('x86_64')
url="https://ffmpeg.org/"
license=('LGPL2.1')
source=("http://repo.herecura.eu/herecura/x86_64/${pkgname}-codecs-${pkgver}-1-x86_64.pkg.tar.xz")
md5sums=('991f8df7fa51d140fc0a7583074b80af')

package() {
  cd opt/vivaldi
  install -Dm644 libffmpeg.so "$pkgdir"/opt/vivaldi/lib/libffmpeg.so
}
