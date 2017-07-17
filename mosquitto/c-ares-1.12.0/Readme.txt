
install autoconf & libtool

cd c-ares-cares-1_12_0
./buildconf 
./configure --host=mipsel-linux --prefix=/home/sanchrist/Desktop/c-ares-1.12.0
make
make install
