cmake_minimum_required(VERSION 3.0)
project(formatter_ex)
file(GLOB CPPS "*.cpp")
include_directories(${CMAKE_SOURCE_DIR}/../formatter_lib)
find_library(LIB_PATH formatter "${CMAKE_SOURCE_DIR}/../formatter_lib/build")
add_library(formatter_ex STATIC ${CPPS} "formatter_ex.h")
target_link_libraries(formatter_ex ${LIB_PATH})



