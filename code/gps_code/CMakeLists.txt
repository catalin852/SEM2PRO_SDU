cmake_minimum_required(VERSION 2.8)
set (CMAKE_C_FLAGS "-Wall -Wextra")

project(gps_code)

#Bring the headers into the project
include_directories(include)

#However, the file(GLOB...) allows for wildcard additions:
file(GLOB SOURCES "src/*.c")
add_executable(gps_code ${SOURCES})
