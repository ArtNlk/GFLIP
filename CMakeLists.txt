cmake_minimum_required(VERSION 3.14)

project(GFLIP LANGUAGES CXX)

set(CMAKE_INCLUDE_CURRENT_DIR ON)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(GFLIP STATIC
  gflip.cpp
  gflip.h
)

target_compile_definitions(GFLIP PRIVATE GFLIP_LIBRARY)
