# cmake_minimum_required(VERSION <specify CMake version here>)
#set(CMAKE_LEGACY_CYGWIN_WIN32 0)
cmake_minimum_required(VERSION 3.19)
project(pintos C)

set(CMAKE_C_STANDARD 99)
include_directories(src src/lib src/lib/kernel src/lib/user)
add_executable(pintos main.c)