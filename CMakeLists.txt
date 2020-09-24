cmake_minimum_required(VERSION 3.15)
project(csapp_sample C)

set(CMAKE_C_STANDARD 99)

include_directories(./code/include)

add_executable(csapp_sample main.c ./code/src/csapp.c)