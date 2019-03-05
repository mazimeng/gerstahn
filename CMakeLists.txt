cmake_minimum_required(VERSION 3.10)
project(socks5)

set(CMAKE_CXX_STANDARD 11)

add_executable(socks5 main.cpp)

target_link_libraries(socks5 ev)
