# Maintainer: Andrwe Lord Weber <lord-weber-andrwe [at]  ndrwe [dot] org>
# Contributor: dan saul <aur dot cryingwolf at org>
_realname=transmissionrpc
pkgname=py${_realname}
pkgver=0.8
pkgrel=1
pkgdesc="A python module that communicate with Transmission through json-rpc e.g. for FlexGet."
arch=(any)
url="http://bitbucket.org/blueluna/transmissionrpc/wiki/Home"
license=MIT
depends=("python2")
source=(http://pypi.python.org/packages/source/t/transmissionrpc/${_realname}-${pkgver}.tar.gz)
md5sums=('3fe59c513144388b4e8e2970e8bb9ebe')

build() {
  cd ${srcdir}/${_realname}-${pkgver}/ || return 1
  mkdir -p ${pkgdir}/usr/lib/python2.7/site-packages || return 1
  cp -r ${_realname} ${pkgdir}/usr/lib/python2.7/site-packages || return 1
}
