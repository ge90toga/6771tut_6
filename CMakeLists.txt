cmake_minimum_required(VERSION 3.5)
project(6771tut_week7_part1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES variadicPrint.cpp)
add_executable(6771tut_week7_part1 ${SOURCE_FILES})