cmake_minimum_required(VERSION 3.8 FATAL_ERROR)
project(vectAdd LANGUAGES CXX CUDA)

add_executable(out main.cpp)
add_library(greyscale SHARED greyscale.cu)