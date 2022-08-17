# build-system
The repository contains the different COPASI build systems.

## Getting started:
To build a stable version of COPASI Version 4.35 do

```bash
git clone git@github.com:copasi/build-system.git
source build-system/profile/...
emerge
install-dependencies
release --branch release/Version-4.35 --comment stable
```
where you source the appropriate profile

### Building on Darwin-Intel
Since we have several build environments for macOS, here the specific example of how to install it on an intel machine. To setup the complete build environment on macOS Big Sur. First install `brew`, then install: 

```bash 
brew install coreutils
```

now checkout the project, into `$HOME/build-system-intel`, and proceed as in the above: 

```bash
cd
git clone https://github.com/copasi/build-system.git build-system-intel
source build-system-intel/profile/darwin-intel
emerge
install-dependencies
release --branch release/Version-4.37 --comment stable --noscp
```

To make minor adjustments to the build, such as the target SDK, target qt version or such, you'd modify the `build-system-intel/variables/darwin-intel`.
