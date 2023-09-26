cmake_minimum_required(VERSION 3.0)

project(Math)

add_executable(main_file main.cpp)

add_subdirectory(src)

include_directories(header)

target_link_libraries(main_file PRIVATE calc)