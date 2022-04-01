cmake_minimum_required(VERSION 3.0)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
project(solver)
file(GLOB CPPS "*.cpp")
add_library(solver STATIC ${CPPS} "solver.h")
target_link_libraries(solver)


