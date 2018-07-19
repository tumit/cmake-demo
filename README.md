# CMake Demo
try to use cmake in simple cpp project

## 00 Simple compile
  - g++ FizzBuzz.cc

## First CMake
  - `cmake -H. -Bbuild`
    -H points the source tree root.
    -B points the build directory.
  - `cmake --build build`
  - run compiled by `./FizzBuzz`
