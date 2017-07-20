cmake_minimum_required(VERSION 3.7)
project(Progra3Tarea1_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bin/Debug/Tarea1
        obj/Debug/Evaluador.o
        obj/Debug/main.o
        Evaluador.cpp
        Evaluador.h
        LICENSE
        main.cpp
        README.md
        Tarea1.cbp
        Tarea1.depend
        Tarea1.layout)

add_executable(Progra3Tarea1_master ${SOURCE_FILES})