pkgname=easyarch-calamares-settings
pkgver=2.0.0
pkgrel=2
pkgdesc="EasyArch Calamares Settings"
arch=('any')
url=https://github.com/easyarch-iso
source=("$pkgname-$pkgver::git+$url/easyarch-calamares-settings.git")
sha256sums=('SKIP')
options=(!strip)
package() {
    cd $srcdir/$pkgname-$pkgver
    make DESTDIR="$pkgdir" install
}
