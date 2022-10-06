# expl01
Setup *VSCode* with *CodeLLDB* debugger.

# 1. Setup
```sh
$ mkdir build
$ cd build
$ cmake --version
$ cmake -G "Unix Makefiles" -DCMAKE_BUILD_TYPE=Debug ..
$ make -j8

~/workspace_c++/expl01/build$ ll src
total 72
drwxr-xr-x 3 ryan ryan  4096 Oct  5 22:37 ./
drwxr-xr-x 4 ryan ryan  4096 Oct  5 22:37 ../
drwxr-xr-x 4 ryan ryan  4096 Oct  5 22:37 CMakeFiles/
-rw-r--r-- 1 ryan ryan  6905 Oct  5 22:37 Makefile
-rw-r--r-- 1 ryan ryan  1130 Oct  5 22:37 cmake_install.cmake
-rwxr-xr-x 1 ryan ryan 40888 Oct  5 22:37 gen_id*
-rw-r--r-- 1 ryan ryan  4490 Oct  5 22:37 libgenerate_id.a
```

# VSCode Build & Debug
* Press `ctl-shift-b` to build.
* Press `ctl-shift-p` (command palette) and select 'CMake: Select a kit' to select a compiler.
* Press `ctl-shift-p` (command palette) and select 'CMake: Build Target' to build.
* Press `F5` to start debugging.

