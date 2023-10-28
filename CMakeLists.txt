cmake_minimum_required(VERSION 3.26)
project(AES_encryption C)


set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=address,leak,undefined")

set(CMAKE_C_STANDARD 11)

add_executable(AES_encryption main.c
        testes.c
        teste.c)

