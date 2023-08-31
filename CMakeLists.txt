cmake_minimum_required(VERSION 3.26)
project(John_Conway_Game_of_life C)

set(CMAKE_C_STANDARD 11)

include_directories(game_life)

add_executable(John_Conway_Game_of_life
        game_life/BMP.c
        game_life/BMP.h
        game_life/GameLife.c
        game_life/GameLife.h
        game_life/main.c)
