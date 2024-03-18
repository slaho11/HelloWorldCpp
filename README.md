# Description
Hello world program in C++ using [{fmt}](https://github.com/fmtlib/fmt) formatting library.

# Build and Run

```bash
mkdir build
cd build
cmake ..
cmake --build .
./HelloWorld
```

## CMake presets

To List available presets run:

```bash
cmake --list-presets
cmake --build --list-presets
```

For example, to build with Clang on macOS run:

```bash
cmake --preset release-clang-macos
cmake --build --preset clang-macos
./build/release-clang-macos/HelloWorld
```
