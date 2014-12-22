***Msp430 Gcc Toolchain***

An unofficial Msp430 Gcc Toolchain and pre-builds.

You can clone the pre-builds only with

```
git clone "git@github.com:cwyark/msp430-gcc-toochain.git"
```

Or you can clone the mspgcc tool chain and pre-builds using...

```
git clone --recursive "git@github.com:cwyark/msp430-gcc-toochain.git"
```

There are three parts of the msp430 gcc toolchain.

1. binutils 2.22

configure parameter: ./configure --target=msp430 --prefix=${PROJECT_ROOT}/build/${OS}/${ARCH}

compiled commit: d5323c6db0d12aa3b5ece782fc52f168417db167

2. gcc

configure parameter: ./configure --target=msp430 --enable-languages=c,c++ --prefix=${PROJECT_ROOT}/build/${OS}/${ARCH}

3. gdb

configure parameter: ./configure --target=msp430 --prefix=${PROJECT_ROOT}/build/${OS}/${ARCH}
