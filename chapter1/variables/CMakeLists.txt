cmake_minimum_required(VERSION 3.0)

project("varibales" VERSION 1.0 
DESCRIPTION "A simple project to demonstrate basic CMake usage"
LANGUAGES CXX)

set(MYVAR "1234")
message(STATUS "The content of MYVAR are ${MYVAR}")
#Variables references can even be nested and are evaluated inside out
# ${outer_${inner_variable}_variable}