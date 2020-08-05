cmake_minimum_required(VERSION 3.18)

project(shell)

set(SOURCES src/main.c src/prompt.c)

add_executable(shell ${SOURCES})
target_include_directories(shell PRIVATE include)