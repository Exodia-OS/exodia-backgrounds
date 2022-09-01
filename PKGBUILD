#
# Maintainer: Mahmoud Mohamed (Ozil) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-backgrounds
pkgver=1.0
pkgrel=6
pkgdesc="Backgrounds For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-backgrounds"
license=('GPL3')

prepare() {

	cp -af ../backgrounds/. ${srcdir}

}

package() {

	local backgrounds_dir=${pkgdir}/usr/share/backgrounds
	mkdir -p "$backgrounds_dir"
	cp -r ${srcdir}/* "$backgrounds_dir"

}
