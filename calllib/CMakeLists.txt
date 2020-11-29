cmake_minimum_required(VERSION 2.8)

project(calllib)

add_subdirectory(test)

add_executable(calllib main.cpp)

target_link_libraries(calllib test)