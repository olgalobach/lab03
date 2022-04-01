cmake_minimum_required(VERSION 3.0)
project(formatter)
file(GLOB CPPS "*.cpp")
add_library(formatter STATIC ${CPPS} "formatter.h")
