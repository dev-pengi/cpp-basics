cmake_minimum_required(VERSION 3.5.0)
project(basics VERSION 0.1.0 LANGUAGES C CXX)

add_executable(basics main.cpp)
target_compile_options(basics PUBLIC -g -Wall -Wextra)

