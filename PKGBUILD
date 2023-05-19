#
# Contribuidor: {{ nome_do_autor(); }}
#

pkgname=base
pkgver=3
pkgrel=1
pkgdesc='Pacote mínimo definido para definir uma instalação básica do sistema.'
url='http://localhost/base'
arch=('any')
license=('cIO')

depends=(
    #
    # Muito muito básico.
    #
    'filesystem' 'gcc-libs' 'glibc' 'bash'

    #
    # Ferramentas POSIX.
    #
    'coreutils' 'file' 'findutils' 'gawk' 'grep' 'procps-ng' 'sed' 'tar'

    #
    # Conjunto de ferramentas do sistema padrão.
    #
    'gettext' 'pciutils' 'psmisc' 'shadow' 'util-linux' 'bzip2' 'gzip' 'xz'

    #
    # Requisitos definidos pelo sistema.
    #
    'licenses' 'pacman' 'archlinux-keyring' 'systemd' 'systemd-sysvcompat'

    #
    # Rede, ping, etc.
    #
    'iputils' 'iproute2'
)

optdepends=('linux: Suporte padrão do núcleo')
