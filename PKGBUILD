# Contributor: Bhushan Shah < bshah at kde dot org >
pkgname=android-headers-28
pkgver=9.0.0
pkgrel=1
pkgdesc="Android headers extracted through libhybris"
arch=('any')
url="https://github.com/droidian/android-headers-28"
license=('Apache')
makedepends=('git' 'libffi')
provides=('android-headers')
conflicts=('android-headers-29')
source=('android-headers::git+https://github.com/droidian/android-headers-28')
md5sums=('SKIP')

package() {
    cd android-headers
    make PREFIX="/usr" DESTDIR="$pkgdir/" install
}


