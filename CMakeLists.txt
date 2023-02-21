cmake_minimum_required(VERSION 3.24)
project(ceeTest1 C)

set(CMAKE_C_STANDARD 99)

add_executable(ceeTest1 main.c adder.h adder.c)
