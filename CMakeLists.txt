cmake_minimum_required(VERSION 3.8)

project(sh_physim)

set(CMAKE_EXE_LINKER_FLAGS "-static")

add_executable(${PROJECT_NAME} "main.cpp")