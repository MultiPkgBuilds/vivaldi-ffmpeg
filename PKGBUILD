pkgname=vivaldi-ffmpeg
pkgver=50.0.2661.89
pkgrel=1
pkgdesc='Additional support for proprietary codecs for vivaldi.'
arch=('x86_64')
url="https://ffmpeg.org/"
license=('LGPL2.1')
source=("http://repo.herecura.eu/herecura/x86_64/${pkgname}-codecs-${pkgver}-1-x86_64.pkg.tar.xz")
md5sums=('82b5f79c12851952a735ddd04ba38472')

package() {
  cd opt/vivaldi
  install -Dm644 libffmpeg.so "$pkgdir"/opt/vivaldi/lib/libffmpeg.so
}
