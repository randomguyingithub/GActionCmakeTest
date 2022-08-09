cmake_minimum_required(VERSION 3.23)
project(testing)
add_subdirectory(src)
add_executable(Main
  src/main.cpp
)
