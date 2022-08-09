cmake_minium_required(VERSION 2.8)
project(testing)
add_subdirectory(src)
add_executable(Main
  src/main.cpp
)
