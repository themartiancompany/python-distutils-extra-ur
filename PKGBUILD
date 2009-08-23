# Maintainer: Abhishek Dasgupta <abhidg@gmail.com>
# Contributor: Abhishek Dasgupta <abhidg@gmail.com>

pkgname=python-distutils-extra
pkgver=2.9
pkgrel=1
pkgdesc="Enhancements to the Python build system"
arch=(any)
license=("GPL")
url="http://packages.qa.debian.org/p/python-distutils-extra.html"
depends=('intltool' 'python>=2.6')
makedepends=('setuptools')
source=(http://ftp.de.debian.org/debian/pool/main/p/${pkgname}/${pkgname}_${pkgver}.tar.gz)

build() {
  cd "${srcdir}/debian"
  python setup.py install --root="${pkgdir}" || return 1
}

md5sums=('98ab4fe803d103ad57a51a3184df5dc8')
