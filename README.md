# clang-12-ndk
Clang-12 ndk toolchain for android aarch64 (arm64-v8)
# Usage
```
LD_LIBRARY_PATH=lib TMPDIR=tmp ./bin/clang-12 -Iinclude -Iinclude/aarch64-linux-android --sysroot=/data/media/0/clang-12-ndk test.c -o test
```
# credits
Termux organization
