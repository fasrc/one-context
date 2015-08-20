# Maintainer Harvard University FAS Research Computing <rchelp.fas.harvard.edu>

pkgname=one-context
pkgver=4.14.1
pkgrel=1
pkgdesc='OpenNebula Contextualisation'
arch=('any')
url='https://github.com/OpenNebula/addon-context-linux/releases'
license=('Apache')
depends=()
source=("https://github.com/fasrc/addon-context-linux/archive/v4.14.1.2.tar.gz")
install=one-context.install

package() {
    cp -rT ${srcdir}/addon-context-linux-4.14.1.1/base_arch/etc ${pkgdir}
    cp -rT ${srcdir}/addon-context-linux-4.14.1.1/base_arch/usr ${pkgdir}
    cp -rT ${srcdir}/addon-context-linux-4.14.1.1/base/etc ${pkgdir}
    cp -rT ${srcdir}/addon-context-linux-4.14.1.1/base/usr ${pkgdir}
    cp -rT ${pkgdir}/usr/sbin ${pkgdir}/usr/bin
    rm -rf ${pkgdir}/usr/sbin
}
md5sums=('cd2fe6a0f01fcc7167509c8013bdaa95')