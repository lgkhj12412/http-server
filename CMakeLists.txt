cmake_minimum_required(VERSION 3.20)
project(http_server CXX)

set(CMAKE_CXX_STANDART 20)
set(CMAKE_CXX_STANDART_REQUIRED ON)

find_package(Threads REQUIRED)

add_executable(server src/main.cpp)
target_link_libraries(server PRIVATE Threads::Threads)
