# Maintainer: Roger Bassons "rogertux" <rogerbassons@gmail.com>
pkgname=tv3gnulinuxcat
pkgver=0.76
pkgrel=0
epoch=
pkgdesc="Download videos from TV3"
arch=(any)
url="http://www.gnulinux.cat/"
license=('GPL3')
groups=()
depends=('zenity' 'vlc' 'wget')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=changelog
source=(http://sourceforge.net/projects/gnulinuxcattv3/files/tv3-v${pkgver}.tar.gz/download)
noextract=()
md5sums=('20c37590406b998d6bf35c08375b3733')


package() {
  cd "${srcdir}"
  mkdir -p $pkgdir/usr/bin
  mkdir -p $pkgdir/usr/share/icons
  mkdir -p $pkgdir/usr/share/applications
  install -Dm755 gnulinuxcattv3-code/tv3 $pkgdir/usr/bin/
  install -Dm644 gnulinuxcattv3-code/deb/tv3-icon.png $pkgdir/usr/share/icons
  install -Dm644 gnulinuxcattv3-code/deb/tv3.desktop $pkgdir/usr/share/applications/tv3.desktop
 }
