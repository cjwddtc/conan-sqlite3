project(sqlite3)
cmake_minimum_required(VERSION 2.8)

include(../conanbuildinfo.cmake)
conan_basic_setup()

add_library(sqlite3 sqlite3.c)

