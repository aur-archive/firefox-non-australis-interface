# Maintainer: Kamil Wisniewski (FORMOZA) <formoza@autistici.org>

pkgname=firefox-non-australis-interface
pkgver=28.0
pkgrel=2
pkgdesc="Mozilla Firefox with classic interface (non-australis)"
arch=(x86_64)
url=http://mozilla.org/firefox
license=(GPL\LGPL\MPL)
depends=('alsa-lib' 'dbus-glib' 'desktop-file-utils' 'gtk2' 'hicolor-icon-theme' 'hunspell' 'icu' 'libevent' 'libvpx' 'libxt' 'mime-types' 'mozilla-common' 'nss' 'startup-notification')
install=$pkgname.install
provides=($pkgname)
source=(https://ftp.mozilla.org/pub/mozilla.org/firefox/releases/28.0/linux-x86_64/en-US/firefox-28.0.tar.bz2)
md5sums=(8264fda486828d925aa094de902eb182)

package()
{
  mkdir -p $pkgdir/opt/firefox
  cp -R $srcdir/firefox $pkgdir/opt/
}