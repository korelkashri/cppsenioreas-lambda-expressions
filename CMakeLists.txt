cmake_minimum_required(VERSION 3.17)
project(cppsenioreas_lambda_expressions)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17 -pthread")

add_executable(cppsenioreas_lambda_expressions main.cpp)