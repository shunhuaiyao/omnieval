# omnieval

To run remappping code:

Step 1: Build
cd remap
mkdir build
cd build
cmake ../
make

Step 2: Run
Run command help:
./remap

Example 1: conversion from equirectangular (2048x1024) to equalarea (1024x512)
./remap -i rect -o eqar -m 1024 -b 2048 -n 512 -v 1024 rect.yuv eqar.yuv
