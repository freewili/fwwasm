cmake_minimum_required(VERSION 3.25)

project(fwwasm VERSION 0.0.1 LANGUAGES C CXX)

add_library(fwwasm INTERFACE)

target_include_directories(fwwasm INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)