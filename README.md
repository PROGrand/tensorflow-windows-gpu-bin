# tensorflow-windows-gpu-bin
Precompiled [Tensorflow](https://github.com/tensorflow/tensorflow) binaries for latest Windows and CUDA. Primarily for C++.

[tensorflow1.11-windows10-cuda10.0-cudnn7.3-msvc15.8.5-x64-cpp-bin.7z](tensorflow1.11-windows10-cuda10.0-cudnn7.3-msvc15.8.5-x64-cpp-bin.7z) - prebuilt with CUDA arch 5.2 and AVX.

Usage:

Just add <i>extracted-path</i>/lib/tensorflow.lib to LIBRARIES, add <i>extracted-path</i>/include to INCLUDES, copy <i>extracted-path</i>/bin/tensorflow.dll to somewhere in %PATH%. 
