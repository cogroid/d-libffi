all:
	sudo rm -rf /home/cogroid/local/libffi/armv7/*
	sudo mkdir -p /home/cogroid/local/libffi/armv7/bbin
	sudo cp -rf ./bin/* /home/cogroid/local/libffi/armv7/bbin/
	sudo rm -f /home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin/arm-linux-androideabi-cc
	sudo ln -s /home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin/arm-linux-androideabi-gcc /home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin/arm-linux-androideabi-cc
	cd ../../; \
	export PATH="/home/cogroid/local/libffi/armv7/bbin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/arm-linux-androideabi/bin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin:${PATH}"; \
	./configure \
	ABI=32 \
	LDFLAGS=" -v --target=arm-linux-androideabi -march=armv7-a -fPIC -fno-integrated-as --sysroot /home/cogroid/local/android-ndk-r18b/sysroot -isystem /home/cogroid/local/android-ndk-r18b/sysroot/usr/include/arm-linux-androideabi -D__ANDROID_API__=24 -fexceptions -frtti -ffunction-sections -funwind-tables -fstack-protector-strong -Wno-invalid-command-line-argument -Wno-unused-command-line-argument -no-canonical-prefixes -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++/include -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++abi/include -I/home/cogroid/local/android-ndk-r18b/sources/android/support/include -DANDROID -Wa,--noexecstack -Wformat -Werror=format-security -DNDEBUG -O2 -L/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -B/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -L/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb -B/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb" \
	CFLAGS=" -v --target=arm-linux-androideabi -march=armv7-a -fPIC -fno-integrated-as --sysroot /home/cogroid/local/android-ndk-r18b/sysroot -isystem /home/cogroid/local/android-ndk-r18b/sysroot/usr/include/arm-linux-androideabi -D__ANDROID_API__=24 -fexceptions -frtti -ffunction-sections -funwind-tables -fstack-protector-strong -Wno-invalid-command-line-argument -Wno-unused-command-line-argument -no-canonical-prefixes -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++/include -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++abi/include -I/home/cogroid/local/android-ndk-r18b/sources/android/support/include -DANDROID -Wa,--noexecstack -Wformat -Werror=format-security -DNDEBUG -O2 -L/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -B/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -L/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb -B/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb" \
	CPPFLAGS=" -v --target=arm-linux-androideabi -march=armv7-a -fPIC -fno-integrated-as --sysroot /home/cogroid/local/android-ndk-r18b/sysroot -isystem /home/cogroid/local/android-ndk-r18b/sysroot/usr/include/arm-linux-androideabi -D__ANDROID_API__=24 -fexceptions -frtti -ffunction-sections -funwind-tables -fstack-protector-strong -Wno-invalid-command-line-argument -Wno-unused-command-line-argument -no-canonical-prefixes -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++/include -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++abi/include -I/home/cogroid/local/android-ndk-r18b/sources/android/support/include -DANDROID -Wa,--noexecstack -Wformat -Werror=format-security -DNDEBUG -O2 -L/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -B/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -L/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb -B/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb" \
	CXXFLAGS=" -v --target=arm-linux-androideabi -march=armv7-a -fPIC -fno-integrated-as --sysroot /home/cogroid/local/android-ndk-r18b/sysroot -isystem /home/cogroid/local/android-ndk-r18b/sysroot/usr/include/arm-linux-androideabi -D__ANDROID_API__=24 -fexceptions -frtti -ffunction-sections -funwind-tables -fstack-protector-strong -Wno-invalid-command-line-argument -Wno-unused-command-line-argument -no-canonical-prefixes -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++/include -I/home/cogroid/local/android-ndk-r18b/sources/cxx-stl/llvm-libc++abi/include -I/home/cogroid/local/android-ndk-r18b/sources/android/support/include -DANDROID -Wa,--noexecstack -Wformat -Werror=format-security -DNDEBUG -O2 -L/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -B/home/cogroid/local/android-ndk-r18b/platforms/android-24/arch-arm/usr/lib -L/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb -B/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/lib/gcc/arm-linux-androideabi/4.9.x/armv7-a/thumb" \
	--build=i386-linux-gnu \
	--host=arm-linux-androideabi \
	--prefix=/home/cogroid/local/libffi/armv7 \
	--docdir=/home/cogroid/local/libffi/armv7/share/doc/libffi-3.2.1; \

update_makefile:
	cd ../../; \
	./make/armv7/chmkfl.sh

build:
	cd ../../; \
	export PATH="/home/cogroid/local/libffi/armv7/bbin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/arm-linux-androideabi/bin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin:${PATH}"; \
	make

clean:
	cd ../../; \
	make clean

install:
	sudo rm -rf /home/cogroid/local/libffi/armv7/*
	sudo sh -c 'cd ../../; \
	export PATH="/home/cogroid/local/libffi/armv7/bbin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/arm-linux-androideabi/bin:/home/cogroid/local/android-ndk-r18b/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64/bin:${PATH}"; \
	make install;'
	sudo mkdir -p /home/cogroid/local/libffi/armv7/lib
	sudo cp -f ../../arm-unknown-linux-androideabi/.libs/libffi.so.6.0.4 /home/cogroid/local/libffi/armv7/lib/
	sudo ln -s /home/cogroid/local/libffi/armv7/lib/libffi.so.6.0.4 /home/cogroid/local/libffi/armv7/lib/libffi.so.6
	sudo ln -s /home/cogroid/local/libffi/armv7/lib/libffi.so.6.0.4 /home/cogroid/local/libffi/armv7/lib/libffi.so

