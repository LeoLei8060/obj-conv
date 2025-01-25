cmake_minimum_required(VERSION 3.5.1)
project(unit_test)

# Set C++17 as the standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(${PROJECT_NAME} "test.cpp" ${SRC_LIST_FILES})