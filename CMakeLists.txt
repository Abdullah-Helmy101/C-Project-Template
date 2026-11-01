cmake_minimum_required(VERSION 3.20)

project(project LANGUAGES C)

set(CMAKE_C_STANDARD 23)

add_executable(main
    src/main.c
)

target_include_directories(main PRIVATE
    ${CMAKE_INCLUDE_CURRENT_DIR}/include
)