cmake_minimum_required(VERSION 3.2)
project(Clion_F1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Clion_F1 ${SOURCE_FILES})