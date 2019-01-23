cmake_minimum_required(VERSION 3.12.3)
project(algorithms C)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c99")

set(CMAKE_C_STANDARD 99)

add_executable(
        algorithms
        test/bogo_sort_test.c


)