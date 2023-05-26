cmake_minimum_required(VERSION 3.10)

project(my_project)

set(CMAKE_CXX_STANDARD 11)

# Add source files
file(GLOB SOURCES "src/*.cpp")

# Create executable
add_executable(my_project ${SOURCES})