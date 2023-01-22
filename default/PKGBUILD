#
# Maintainer: Mahmoud Mohamed (00xWolf) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-backgrounds
pkgver=2.0
pkgrel=4
pkgdesc="Backgrounds For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-backgrounds"
license=('GPL3')
groups=('exodia-backgrounds-all')
prepare() {

	cp -af ../backgrounds/. ${srcdir}

}

package() {

	local backgrounds_dir=${pkgdir}/usr/share/backgrounds
	mkdir -p "$backgrounds_dir"
	cp -r ${srcdir}/* "$backgrounds_dir"

}
