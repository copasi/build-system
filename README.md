# build-system
The repository contains the different COPASI build systems.

## Getting started:
```
git clone git@github.com:copasi/build-system.git
cd build-system
git checkout [linux-32|linux-64|darwin|darwin-intel|darwin-arm]
bin/emerge
source build-system/.variables
install-dependencies
release --noscp --branch ...
```
You may have to edit the `.variables` and `bin/build` files to adopt for your system.

## Supported environments
* [Linux 32 bit](https://github.com/copasi/build-system/tree/linux-32) 
* [Linux 64 bit](https://github.com/copasi/build-system/tree/linux-64) 
* [Mac OS X 12 (arm)](https://github.com/copasi/build-system/tree/darwin-arm)
* [Mac OS X 12 (intel)](https://github.com/copasi/build-system/tree/darwin-intel)
* [Mac OS X](https://github.com/copasi/build-system/tree/darwin)
