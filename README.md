# x264-msvc

## What's x264-msvc?
x264-msvc is a fork of x264 project, compatible with Microsoft Visual C++.

Now, x264-msvc is based on x264-snapshot-20141218-2245, and is built successfully on Visual Studio 2013 (VC12).


## Why x264-msvc?
* For getting rid of dependency of MSYS/MinGW when you debugging it on Windows Platform;
* For studing H.264 and x264 in deep by debugging it in Visual Studio;



## How to use x264-msvc?
### 1. Build
Just open x264-msvc.sln by Visual Studio 2013 (or higher) and build it.
### 2. Run
Use x264-msvc.exe with arguments (e.g.  x264-msvc.exe -o a.avc a.yuv --input-res 352x288)


## TODO
### 1. enable yasm support


## LICENCE
GNU GPL

## Reference
* http://www.videolan.org/developers/x264.html
