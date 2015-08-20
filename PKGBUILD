# Maintainer Dan Kelleher <dkelleher@g.harvard.edu>

pkgname=one-context
pkgver=4.14.1
pkgrel=1
pkgdesc='OpenNebula Contextualisation'
arch=('any')
url='https://github.com/OpenNebula/addon-context-linux/releases'
license=('Apache')
depends=()
source=("https://github.com/fasrc/addon-context-linux/archive/v4.14.1.1.tar.gz")
install=one-context.install

package() {
    cp -rT ${srcdir}/addon-context-linux-4.14.1.1/base_arch ${srcdir}/addon-context-linux-4.14.1.1/base
    mv ${srcdir}/addon-context-linux-4.14.1.1/base/etc ${pkgdir}
    mv ${srcdir}/addon-context-linux-4.14.1.1/base/usr ${pkgdir}
    cp -rT ${pkgdir}/usr/sbin ${pkgdir}/usr/bin
    rm -rf ${pkgdir}/usr/sbin
}
md5sums=('344af6823bc2942f7557a4df7a0bf06d')