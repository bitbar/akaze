# Testdoir Akaze fork

This is a fork of the official
[Akaze](https://github.com/pablofdezalc/akaze.git) repo, with added
support for json communication. This is to be used with Testdroid
[image recognition
samples](https://github.com/bitbar/testdroid-samples/tree/master/image-recognition).

## Current Akaze Version

Version: 1.5.0
Date: 11-12-2014

You can get the latest version of the code from github:
`https://github.com/pablofdezalc/akaze`


## Library Dependencies

The code is mainly based on the OpenCV library using the C++ interface

In order to compile the code, the following libraries are needed on your system:
- OpenCV version 2.4.0 or higher
- Cmake version 2.6 or higher

You will also need **doxygen** in case you need to generate the documentation

Tested systems:
- Mac OSX Yosemite

## Getting Started

Compiling:

1. `$ mkdir build`
2. `$ cd build>`
3. `$ cmake ..`
4. `$ make`

If the compilation is successful you should see three executables in the folder bin:
- `akaze_features`
- `akaze_match`
- `akaze_compare`

Additionally, the library `libAKAZE[.a, .lib]` will be created in the folder `lib`.

If there is any error in the compilation, perhaps some libraries are missing.
Please check the Library dependencies section.

## Using Compiled Binaries

Copy the generated binaries from build/bin/ directory to your
image-recognition/akaze/bin/ directory. Checkout the [image
recognition
sample](https://github.com/bitbar/testdroid-samples/tree/master/image-recognition)
on how to use these binaries.
