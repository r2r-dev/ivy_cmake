PROJECT(calcexe)

cmake_minimum_required(VERSION 2.6)

set(LIBRARY_OUTPUT_PATH build/lib)
set(EXECUTABLE_OUTPUT_PATH build/bin)

# Main executable
SET(SOURCES src/main/cpp/main.cpp)

INCLUDE_DIRECTORIES(resources/include)

LINK_DIRECTORIES(resources/lib)	

ADD_EXECUTABLE(calcexe ${SOURCES})

target_link_libraries(calcexe calc)
