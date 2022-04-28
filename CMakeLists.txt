cmake_minimum_required(VERSION 3.0)
include_directories("${CMAKE_SOURCE_DIR}/formatter_ex_lib" "${CMAKE_SOURCE_DIR}/formatter_lib" "${CMAKE_SOURCE_DIR}/solver_lib")
project(lab04)
<<<<<<< HEAD
#find_library(LIB_PATH2 formatter_ex "${CMAKE_SOURCE_DIR}/formatter_ex_lib/build")
=======
>>>>>>> 0efc78565bb19c44f2197a63e5991f4683703c0a
add_subdirectory(hello_world_application)
add_subdirectory(solver_application)

