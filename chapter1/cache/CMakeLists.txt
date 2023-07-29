cmake_minimum_required(VERSION 3.0)

project("chapter1" VERSION 1.0 
DESCRIPTION "A simple project to demonstrate basic CMake usage"
LANGUAGES CXX)

set(ch1_MYVAR foo CACHE STRING "Variable foo that configures bar")