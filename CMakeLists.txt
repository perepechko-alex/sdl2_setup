cmake_minimum_required(VERSION 3.25)
project(projectName)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${PROJECT_SOURCE_DIR}/cmake")

find_package(SDL2 REQUIRED)
include_directories(${SDL2_INCLUDE_DIR})

add_executable(projectName main.cpp)
target_link_libraries(projectName ${SDL2_LIBRARY})
