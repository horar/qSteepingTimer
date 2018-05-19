cmake_minimum_required(VERSION 3.11 FATAL_ERROR)

project(qSteepingTimer)

set(CMAKE_INCLUDE_CURRENT_DIR ON)
set(CMAKE_AUTOMOC ON)

find_package(Qt5Core)

add_subdirectory(gui)
