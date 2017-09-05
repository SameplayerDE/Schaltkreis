cmake_minimum_required(VERSION 3.8)
project(Schaltkreis)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES frame.cpp)
add_executable(Schaltkreis ${SOURCE_FILES})