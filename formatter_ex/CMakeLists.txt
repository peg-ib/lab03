cmake_minimum_required(VERSION 3.4)
project(formatter_ex)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_library(formatter_exlib STATIC /formatter_ex.cpp)
add_executable(formatter_ex /formatter_ex.cpp)
target_link_libraries(formatter_ex formatter_exlib)
