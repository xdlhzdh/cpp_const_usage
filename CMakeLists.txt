cmake_minimum_required(VERSION 3.18.4 FATAL_ERROR)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")

file(GLOB SOURCES "*.cpp")
add_executable(main ${SOURCES})
