# Maintainer: OrdinaryMagician <saniukeokusainaya@gmail.com>
pkgname=profile-sync-daemon-rc
pkgver=5.28
pkgrel=1
pkgdesc="initscripts support for the profile-sync-daemon package"
arch=("any")
license=("GPL")
depends=("profile-sync-daemon>=${pkgver}")
source=("https://dl.dropbox.com/u/3619130/antisystemd/rcscripts/psd")
url=("https://dl.dropbox.com/u/3619130/antisystemd/about.html")
md5sums=("059a9a4f781aa470cbaead608093667d")

package() {
  cd "${srcdir}"
  install -Dm755 psd "${pkgdir}/etc/rc.d/psd"
}
