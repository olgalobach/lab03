cmake_minimum_required(VERSION 3.0)
project(hello_world)
include_directories(${CMAKE_SOURCE_DIR}/formatter_ex_lib)
find_library(LIB_PATH2 formatter_ex "${CMAKE_SOURCE_DIR}/formatter_ex_lib/build")
find_library(LIB_PATH_2 formatter "${CMAKE_SOURCE_DIR}/formatter_lib/build")
add_executable(hello_world hello_world.cpp)
target_link_libraries(hello_world ${LIB_PATH2} ${LIB_PATH_2})
