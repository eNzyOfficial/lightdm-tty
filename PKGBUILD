# Maintainer: Sarah Kraßnigg <buckling.spring@mailbox.org>
_pkgname=lightdm-tty
pkgname=lightdm-webkit2-theme-tty
pkgver=1.0.0
pkgrel=1
pkgdesc="A simple terminal style theme for lightdm-webkit2-greeter"
arch=('any')
url="https://github.com/eNzyOfficial/lightdm-tty"
license=('WTFPL')
depends=('lightdm-webkit2-greeter')
makedepends=('git')
source=("git+https://github.com/eNzyOfficial/${_pkgname}.git")
md5sums=('SKIP')

package() {
    install -dm755 "$pkgdir/usr/share/lightdm-webkit/themes/lightdm-tty"
    cp -r "$srcdir/$_pkgname/"* "$pkgdir/usr/share/lightdm-webkit/themes/lightdm-tty/"
}
