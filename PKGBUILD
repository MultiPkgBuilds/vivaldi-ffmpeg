pkgname=vivaldi-ffmpeg
pkgver=49.0.2623.110
pkgrel=1
pkgdesc='Additional support for proprietary codecs for vivaldi.'
arch=('x86_64')
url="https://ffmpeg.org/"
license=('LGPL2.1')
source=("http://repo.herecura.eu/herecura/x86_64/${pkgname}-codecs-${pkgver}-1-x86_64.pkg.tar.xz")
md5sums=('cfa991b9e4156688126ff1d14e74a7a5')

package() {
  cd opt/vivaldi
  install -Dm644 libffmpeg.so "$pkgdir"/opt/vivaldi/lib/libffmpeg.so
}
