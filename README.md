# `tauri-arm`
A dockerfile to build a ARM cross-compiler for Tauri


## Installation

*Please build with at least Docker version*.

#### Build ARMv7 Docker image

    $ yarn init:armv7
    
    or
    
    $ docker build . -t rust_cross_compile/armv7 -f Dockerfile.armv7

#### Build ARM64 Docker image

    $ yarn init:arm64
    
    or
    
    $ docker build . -t rust_cross_compile/arm64 -f Dockerfile.arm64


## Development

    $ yarn dev
    
    
## Build

#### Build for Local

    $ yarn build

#### Build for ARMv7(.deb)

    $ yarn build:armv7
    
    or
    
    $ yarn build:react && docker run --rm -ti -v `pwd`:/app rust_cross_compile/armv7

#### Build for ARM64(.deb)

    $ yarn build:arm64
    
    or
    
    $ yarn build:react && docker run --rm -ti -v `pwd`:/app rust_cross_compile/armv64
