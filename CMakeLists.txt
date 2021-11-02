cmake_minimum_required(VERSION 3.0)

project(lowdbus)

add_executable(lowdbus main.cpp)

install(TARGETS lowdbus RUNTIME DESTINATION bin)
