cmake_minimum_required(VERSION 4.3)
project(tp3 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(tp3
        Quotes_G.c
        Quotes_G.h)
