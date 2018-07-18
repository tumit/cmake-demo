# set cmake minimum version
cmake_minimum_required(VERSION 3.5)

# set project
project(FizzBuzz)

# output dir
set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
set(LIBRARY_OUTPUT_PATH ${CMAKE_BINARY_DIR})

# include dir
include_directories("${PROJECT_SOURCE_DIR}")

# add execuable
add_executable(FizzBuzz ${PROJECT_SOURCE_DIR}/FizzBuzz.cc)
