cmake_minimum_required(VERSION 3.20.0)

project(ChatApp VERSION 1.0.1)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(client)
add_subdirectory(server)
add_subdirectory(src)
add_subdirectory(tests)