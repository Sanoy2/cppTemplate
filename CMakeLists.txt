cmake_minimum_required(VERSION 3.0) # setting this is required
project(app)            # this sets the project name

include_directories(headers)

file(GLOB SOURCES
    src/*.cpp
)

add_executable(app ${SOURCES})