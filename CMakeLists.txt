cmake_minimum_required(VERSION 3.18)

project(shell)

file(GLOB SOURCES "src/*.c" "src/**/*.c")

add_executable(shell ${SOURCES})
target_include_directories(shell PRIVATE include)