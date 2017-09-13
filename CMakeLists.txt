cmake_minimum_required(VERSION 3.7)
project(Tarea6_progra3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Pais.cpp Pais.h NodoNario.cpp NodoNario.h Evaluador.cpp Evaluador.h)
add_executable(Tarea6_progra3 ${SOURCE_FILES})