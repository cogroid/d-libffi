all:
	sudo mkdir -p /home/cogroid/local/libffi/x64
	cd ../../; \
	./configure \
	--prefix=/home/cogroid/local/libffi/x64 \
	--docdir=/home/cogroid/local/libffi/x64/share/doc/libffi-3.2.1; \
	make

clean:
	cd ../../; \
	make clean

install:
	sudo sh -c 'cd ../../; \
	make install;'


