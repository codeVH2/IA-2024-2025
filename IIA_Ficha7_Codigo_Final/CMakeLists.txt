cmake_minimum_required(VERSION 3.24)
project(IIA_Ficha7_Codigo_Final C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(IIA_Ficha7_Codigo_Final
        algoritmo.c
        algoritmo.h
        funcao.c
        funcao.h
        main.c
        utils.c
        utils.h)
