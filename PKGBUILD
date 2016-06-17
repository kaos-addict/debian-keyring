pkgname=debian-archive-keyring
pkgver=2014.3~deb7u1
pkgrel=1
pkgdesc="GnuPG archive keys of the Debian archive"
arch=('x86_64')
url="http://packages.debian.org/sid/debian-archive-keyring"
license=('GPL')
depends=('gnupg')
source=("http://ftp.fr.debian.org/debian/pool/main/d/debian-archive-keyring/${pkgname}_${pkgver}_all.deb")
sha512sums=('8010c52d173cd40e5f7a99d52af58b3e70bc9b64b893dcf180a9204a7de5c4b79ca7a86cdfe96973aa6d0c0baedf6154395ea35d661dd43b46bd8cb61f82aec1')

package() {
        tar xf data.tar.gz -C ${pkgdir}/
}
