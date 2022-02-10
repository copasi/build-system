# build-system
The repository contains the different COPASI build systems.

## Getting started:
To build a stable version of COPASI Version 4.35 do
```
git clone git@github.com:copasi/build-system.git
source build-system/profile/...
emerge
install-dependencies
release --branch release/Version-4.35 --comment stable
```
where you source the appropriate profile
