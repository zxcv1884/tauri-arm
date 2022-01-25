# `tauri-arm`
A dockerfile to build a ARM cross-compiler for Tauri(React Typescript Template).

- [x] MacOS
- [x] Windows 10
- [x] Linux

## Setup

    $ yarn

## Installation

*Please build with at least Docker version*.

#### Build ARMv7 Docker image

    $ yarn init:armv7
    

#### Build ARM64 Docker image

    $ yarn init:arm64


## Development

    $ yarn dev
    
    
## Build

#### Build for Local

    $ yarn build

#### Build for ARMv7(.deb)
###### *Note for Windows: (CMD)Change file package.json \`pwd\` to %cd%*

    $ yarn build:armv7
    

#### Build for ARM64(.deb)
###### *Note for Windows: (CMD)Change file package.json \`pwd\` to %cd%* 
    $ yarn build:arm64
    
