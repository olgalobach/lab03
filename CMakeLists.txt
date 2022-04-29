cmake_minimum_required(VERSION 3.0)
include_directories("${CMAKE_SOURCE_DIR}/formatter_ex_lib" "${CMAKE_SOURCE_DIR}/formatter_lib" "${CMAKE_SOURCE_DIR}/solver_lib")
project(lab04)
add_subdirectory(hello_world_application)
add_subdirectory(solver_application)
./hello_world_application/hello_world

