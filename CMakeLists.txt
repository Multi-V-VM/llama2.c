cmake_minimum_required(VERSION 3.13)
project(llama)

set(CMAKE_CXX_STANDARD 14)

add_executable(llama
    run.c
)
target_link_libraries(llama m)