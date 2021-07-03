cmake_minimum_required(VERSION 2.8)

set(CMAKE_C_COMPILER "gcc-11")
set(CMAKE_CXX_COMPILER "g++-11")
project(test_cmake CXX)

set(CMAKE_CXX_STANDARD 11)

add_executable(a.out test2.cpp)
