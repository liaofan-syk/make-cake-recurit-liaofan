cmake_minimum_required(VERSION 3.10)
project(calculator LANGUAGES C)
include_directories(include)
add_executable(calculator src/main.c src/calculator.c)
