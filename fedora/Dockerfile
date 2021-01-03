FROM fedora:33

RUN dnf install -y git make cmake ccache tar gzip unzip xorg-x11-server-Xvfb pyside2-tools.x86_64 python3-pip\
                   python3-pyside2-devel.x86_64 python3-shiboken2.x86_64 python3-shiboken2-devel.x86_64 g++ clang clang-analyzer qt5-qtbase-devel.x86_64 \
                   qt5-qtsvg-devel.x86_64 catch-devel.x86_64 python3-devel libuuid-devel python3-numpy python3-ddt.noarch ninja-build.x86_64 gcovr rubygems \
                   ruby-devel rubygems-devel.noarch rubygem-nokogiri.x86_64 libxslt-devel.x86_64 libxml2-devel.x86_64 zlib-devel.x86_64 yaml-cpp-devel.x86_64 \
                   gmp-devel.x86_64 /usr/lib/rpm/redhat/redhat-hardened-cc1 && pip3 install meson && gem install git_stats


