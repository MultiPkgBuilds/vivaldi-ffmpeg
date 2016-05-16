pkgname=vivaldi-ffmpeg
pkgver=50.0.2661.102
pkgrel=1
pkgdesc='Additional support for proprietary codecs for vivaldi.'
arch=('x86_64')
url="https://ffmpeg.org/"
license=('LGPL2.1')
source=("http://repo.herecura.eu/herecura/x86_64/${pkgname}-codecs-${pkgver}-1-x86_64.pkg.tar.xz")
md5sums=('88234b0cbfaa321541ec39bb4f9a8de6')

package() {
  cd opt/vivaldi
  install -Dm644 libffmpeg.so "$pkgdir"/opt/vivaldi/lib/libffmpeg.so
}
