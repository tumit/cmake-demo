# set cmake minimum version
cmake_minimum_required(VERSION 3.5)

# set project
project(FizzBuzz)

# output dir
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)

# add execuable
add_executable(FizzBuzz ${PROJECT_SOURCE_DIR}/FizzBuzz.cc)
