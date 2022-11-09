cmake_minimum_required(VERSION 3.23)

project(firmware C CXX ASM)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS ON)
set(CMAKE_C_STANDARD 11)

add_subdirectory(board/stm32f072b-disco)
add_subdirectory(firmware)

