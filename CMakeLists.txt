cmake_minimum_required(VERSION 3.15)
project(src C)

set(CMAKE_C_STANDARD 99)

add_executable(src main.c res.c res.h scanhandler.c scanhandler.h processor.c processor.h builtin.c)