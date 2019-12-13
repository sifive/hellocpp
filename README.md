# hellocpp
A simple "Hello, World!" example to demonstrate printf and build environment for C++ program.

## Steps to build
```
cd freedom-e-sdk
git checkout origin/v201908-hellocpp -b v201908-hellocpp
cd software
git clone git@github.com:sifive/hellocpp.git
cd ..
make PROGRAM=hellocpp TARGET=qemu-sifive-e31 CONFIGURATION=release EXTRA_LIBS="-lstdc++ -lsupc++" clean software
```
