[![Build Status](https://travis-ci.org/mygirl8893/JoftaCoin.svg?branch=master)](https://travis-ci.org/mygirl8893/JoftaCoin)


This is experimental cryptocurrency JoftaCoin (JFT). https://jofta.com

## Building JoftaCoin 

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies:
* Microsoft Visual Studio Community 2017
* cmake-3.11.1
* boost 1.67.0

How to build you can find here: https://www.jofta.com/index.php/2018/05/06/windows-10-clis-for-joftacoin/

Good luck!
