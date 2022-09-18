cmake_minimum_required(VERSION 3.23)
project(COP3402_Assignment_1 C)

set(CMAKE_C_STANDARD 99)

add_executable(COP3402_Assignment_1 driver.c lex.o parser.o vm_skeleton.c)
