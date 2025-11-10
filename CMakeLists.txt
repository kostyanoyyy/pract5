cmake_minimum_required(VERSION 3.10)
project(pr5)

set(CMAKE_C_STANDARD 99)


add_executable(game_signals src/game_signals.c)
add_executable(game_pipe    src/game_pipe.c)
