cmake_minimum_required(VERSION 3.5)
project(Lab3)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    Code3/BinarySearchTree.h
    Code3/dsexceptions.h
    Code3/test2.cpp )

add_executable(Lab3 ${SOURCE_FILES})