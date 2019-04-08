cmake_minimum_required(VERSION 2.8)
project (travis)

if (ENABLE_TESTING MATCHES ON)
add_subdirectory(tests)
endif() 

add_executable(hello main.c)
