cmake_minimum_required(VERSION 3.15)
project(hpc_lab10)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(floyd-warshall)

add_executable(hpc_lab10
        floyd-warshall/floyd-warshall-par.cpp
        floyd-warshall/graph-base.cpp
        floyd-warshall/graph-base.h
        floyd-warshall/graph-utils-par.cpp
        floyd-warshall/graph-utils.h
        blas-dmmmult.cpp
        laplace-common.cpp
        laplace-common.h
        laplace-seq.cpp)
