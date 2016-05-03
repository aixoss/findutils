Environment Variable

export CC=xlc

Run Configure

./configure --prefix=/opt/freware 

To build binaries

make CFLAGS="$CFLAGS" LDFLAGS=-s

Install 

./configure --prefix=/opt/freeware --infodir=/opt/freeware/info --mandir=/opt/freeware/man
mkdir -p /opt/freeware/lib/findutils
make prefix=/opt/freeware install

