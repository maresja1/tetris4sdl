cmake_minimum_required(VERSION 3.2)
project(tetris4sdl)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    config.h
    font.c
    font.h
    highscore.c
    highscore.h
    main.c
    stuff.c
    stuff.h
    tetris.c
    tetris.h)

add_executable(tetris4sdl ${SOURCE_FILES})