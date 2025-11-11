# analytics-core

Tiny C++ + DuckDB analytics starter.
- C++17
- CMake + Ninja
- DuckDB (in-memory or file-backed)
- Example query pipeline

## Build

mkdir -p build && cd build
cmake -G Ninja ..
ninja
./analytics
