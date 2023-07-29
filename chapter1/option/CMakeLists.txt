cmake_minimum_required(VERSION 3.0)

project("chapter1" VERSION 1.0 
DESCRIPTION "A simple project to demonstrate basic CMake usage"
LANGUAGES CXX)

option(CHAPTER1_PRINT_LANGUAGES_EXAMPLES "Print examples for each language" OFF)
include(CMakeDependentOption)