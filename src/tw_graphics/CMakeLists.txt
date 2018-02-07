cmake_minimum_required(VERSION 3.9)
project(twinteractive)

set(ROOT CMAKE_CURRENT_SOURCE_DIR)

set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${ROOT}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${ROOT}/bin)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(tw_graphic)