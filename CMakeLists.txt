cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(test)

find_package(armadillo REQUIRED)

add_library(test main.cpp)

target_link_libraries(test armadillo::armadillo)