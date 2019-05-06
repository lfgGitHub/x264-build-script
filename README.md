# X264-ios-build

script to build lame for iOS

## Usage

* build fat library for all architectures
```
./build-x264.sh
```

* build libraries for specified architectures
```
./build-x264.sh arm64 x86_64
```

* build fat library from thin libraries
```
./build-x264.sh lipo
```
