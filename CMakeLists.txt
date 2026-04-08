cmake_minimum_required(VERSION 3.10)
project(RegexChecker)

set(CMAKE_CXX_STANDARD 17)

# The OJ might replace main.cpp with the test case
add_executable(code main.cpp)
