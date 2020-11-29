cmake_minimum_required(VERSION 2.8)

project(test)

add_library(test STATIC test.cpp)

install(TARGETS test DESTINATION lib)
install(FILES test.h DESTINATION include)

