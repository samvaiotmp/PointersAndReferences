cmake_minimum_required(VERSION 3.7)
project(PointersandReferences)

set(CMAKE_CXX_STANDARD 11)

include_directories(header)

set(SOURCE_FILES src/Person.cpp header/Person.h src/PointersAndReferences.cpp)
add_executable(PointersandReferences ${SOURCE_FILES})