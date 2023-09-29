pkgname=chainctl
pkgver=0.1.175
pkgrel=1
pkgdesc="CLI for the Chainguard Platform"
arch=('x86_64')
url="https://chainguard.dev"
license=('Apache')
provides=("${pkgname}")
conflicts=("${pkgname}")

source_x86_64=("chainctl::https://dl.enforce.dev/chainctl/${pkgver}/chainctl_linux_${arch}")

sha256sums_x86_64=('dcb934ac12c3b44693755d7477af41893e24a36172f56e1b3b8cc8cf27e5a555')

package() {
    install -Dm755 -t "${pkgdir}/usr/local/bin" \
        "chainctl"
}
