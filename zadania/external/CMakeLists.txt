cmake_minimum_required(VERSION 3.10)
add_definitions(-DNDEBUG)
add_definitions(-fPIC)

add_library(external
  isPrime.cpp
)
