Bitcoin Nero (NERO)

## Building Bitcoin Nero

### On Ubuntu 16.04

```
sudo apt-get install build-essential libboost-all-dev git cmake
git clone https://github.com/BitcoinNero/bitcoinnero.git
cd bitcoinnero
make
```

You can see the binaries in the build/src

### On Windows

Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55.

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```
And then do Build.
