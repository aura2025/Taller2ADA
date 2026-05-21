cmake_minimum_required(VERSION 4.2)
project(Taller_2)

set(CMAKE_CXX_STANDARD 20)

add_executable(Taller_2 main.cpp
        "src/Problema 1/EditorTexto.cpp"
        "include/Problema 1/EditorTexto.h"
        "src/Problema 2/Cola.cpp"
        "include/Problema 2/Cola.h"
        "src/Problema 2/Urgencias.cpp"
        "include/Problema 2/Urgencias.h"
        "src/Problema 1/Pila.cpp"
        "include/Problema 1/Pila.h"
        "src/Problema 3/ListaCanciones.cpp"
        "include/Problema 3/ListaCanciones.h"
        "src/Problema 3/ListaEnlazada.cpp"
        "include/Problema 3/ListaEnlazada.h"
        "src/Problema 4/Ventas.cpp"
        "include/Problema 4/Ventas.h"
        "src/Problema 4/TablaHash.cpp"
        "include/Problema 4/TablaHash.h")
