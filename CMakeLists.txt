cmake_minimum_required(VERSION 3.10)

# set the project name
project(CITest2)

# add the executable
add_executable(CITest2 test.cpp)

target_include_directories(CITest2 PUBLIC "${PROJECT_BINARY_DIR}")
