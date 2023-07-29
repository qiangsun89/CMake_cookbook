cmake_minimum_required(VERSION 3.0)

project("chapter1" VERSION 1.0 
DESCRIPTION "A simple project to demonstrate basic CMake usage"
LANGUAGES CXX)

add_executable(hello_world)
target_sources(hello_world PRIVATE main.cpp)