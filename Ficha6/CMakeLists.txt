cmake_minimum_required(VERSION 3.24)
project(Ficha6 C)

set(CMAKE_C_STANDARD 11)

include_directories(CodigoTrepaColinas)

add_executable(Ficha6
        CodigoTrepaColinas/algoritmo.c
        CodigoTrepaColinas/algoritmo.h
        CodigoTrepaColinas/funcao.c
        CodigoTrepaColinas/funcao.h
        CodigoTrepaColinas/main.c
        CodigoTrepaColinas/utils.c
        CodigoTrepaColinas/utils.h)
