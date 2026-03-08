pkgname=obs-service-run
pkgver=2.0.0
pkgrel=0
pkgdesc="Source Service for the OpenSUSE Build Service (OBS)"
arch=('any')
url="https://github.com/qr243vbi/obs-service-run"
license=('GPL3')
groups=('base-devel')
makedepends=('perl' 'bash' )
depends=('perl' 'bash' )
source=("run.pl" "run.service")
sha256sums=('SKIP' 'SKIP')

package() {
  install -Dm755 run.pl "${pkgdir}"/usr/lib/obs/service/run
  install -Dm644 run.service "${pkgdir}"/usr/lib/obs/service/run.service
}
