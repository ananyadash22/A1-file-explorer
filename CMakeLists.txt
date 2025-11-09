cmake_minimum_required(VERSION 3.16)
project(FileExplorer CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(filex main.cpp)

# Warnings are good while developing
if (CMAKE_CXX_COMPILER_ID MATCHES "GNU|Clang")
  target_compile_options(filex PRIVATE -Wall -Wextra -Wpedantic -O2)
endif()
