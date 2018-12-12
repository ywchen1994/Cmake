cmake_minimum_required(VERSION 3.0.0)

project(ex1 VERSION 0.1 LANGUAGES CXX)

set(CMAKE_INCLUDE_CURRENT_DIR ON)
set(CMAKE_AUTOMOC ON)


add_executable(${PROJECT_NAME} main.cpp fool.cpp)


