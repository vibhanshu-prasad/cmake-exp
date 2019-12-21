cmake_minimum_required(VERSION 3.5.1)
project(test_app)

include_directories(include)

set(SOURCES src/main.cpp)

add_executable(test_app ${SOURCES})


