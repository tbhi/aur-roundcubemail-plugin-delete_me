pkgname=roundcubemail-plugin-delete_old
pkgver=1.0.1
pkgrel=1
pkgdesc='A Roundcube plugin to delete messages older than configurable timespans.'
arch=('any')
url='https://github.com/ron4mac/roundcube_delete_old'
license=('GPL3')
depends=('roundcubemail')
source=("https://github.com/ron4mac/roundcube_delete_old/releases/download/v${pkgver}/delete_old.${pkgver}.zip")
sha256sums=('313ad1e2c956130ce6d4b71a81ae3cfb907461ea3bab59a96eed8579d597e1c1')

package() {
    mkdir -p "${pkgdir}/usr/share/webapps/roundcubemail/plugins"
    cp -r "${srcdir}/delete_old" "${pkgdir}/usr/share/webapps/roundcubemail/plugins"
}
