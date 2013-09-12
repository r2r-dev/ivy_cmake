PROJECT(calc)

cmake_minimum_required(VERSION 2.6)
set(CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake)

set(LIBRARY_OUTPUT_PATH build/lib)

# Main executable
SET(SOURCES src/main/cpp/Calculator.cpp)
INCLUDE_DIRECTORIES(resources/include)

ADD_LIBRARY(calc SHARED ${SOURCES})		
