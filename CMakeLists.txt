cmake_minimum_required(VERSION 3.9)

set(CMAKE_ROOT_DIR ${CMAKE_CURRENT_SOURCE_DIR})

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_ROOT_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_ROOT_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_ROOT_DIR}/bin)

set(CMAKE_DEBUG_POSTFIX d)

add_subdirectory(src)
add_subdirectory(test)