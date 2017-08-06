
First method to compile:
cd openssl-1.0.0l/
./config no-asm shared --prefix=/opt/openssl-1.0.0l/build
export cross=mipsel-linux-
delete -m64 in Makefile
make CC="${cross}gcc" AR="${cross}ar r" RANLIB="${cross}ranlib"
make install


2017-08-06 test