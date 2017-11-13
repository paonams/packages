# packages
packages used in buildroot
contains xf86-video-armsoc source code
- compiling option
      - ./configure --with-drmmode=exynos  CC=buildroot/output/host/usr/bin/arm-linux-gnueabihf-gcc CPP=buildroot/output/host/usr/bin/arm-linux-gnueabihf-cpp --prefix=buildroot/output/host/usr/arm-buildroot-linux-gnueabihf/sysroot/usr/ --target=arm  --host=i386-linux PKG_CONFIG=buildroot/output/host/usr/bin/pkg-config
