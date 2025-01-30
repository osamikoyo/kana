cmake_minimum_required(VERSION 3.28)
project(kana C)

set(CMAKE_C_STANDARD 11)

add_executable(kana src/main.c
        src/config.c
        src/config.h
        lib/toml/toml.c
        lib/toml/toml.h)
