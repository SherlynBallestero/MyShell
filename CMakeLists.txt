cmake_minimum_required(VERSION 3.22)
project(Shell__main__history_and_again_ok_ C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(Shell__main__history_and_again_ok_
        controlC.c
        exec.h
        functions.h
        functionsAux.h
        readline.h
        redirect.h
        Shell.c
        shell.h
        variables.h)
