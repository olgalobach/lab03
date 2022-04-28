cmake_minimum_required(VERSION 3.0)
include_directories("${CMAKE_SOURCE_DIR}/formatter_ex_lib" "${CMAKE_SOURCE_DIR}/formatter_lib" "${CMAKE_SOURCE_DIR}/solver_lib")
project(lab04)
#find_library(LIB_PATH2 formatter_ex "${CMAKE_SOURCE_DIR}/formatter_ex_lib/build")
add_subdirectory(hello_world_application)
add_subdirectory(solver_application)

