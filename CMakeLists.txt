cmake_minimum_required(VERSION 3.13)
project(llama)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_C_FLAGS "-lwasi-emulated-mman -D_WASI_EMULATED_MMAN")

add_executable(llama
    run.c
)