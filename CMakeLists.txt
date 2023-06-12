cmake_minimum_required(VERSION 3.24)
project(project6 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(project6
        main.c
        maze_params.h
        project6.c
        recursion.h)
