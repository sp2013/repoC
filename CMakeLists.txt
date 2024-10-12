# Repo C: CMakeLists.txt
cmake_minimum_required(VERSION 3.10)
project(RepoC)

# Create a library target for utils
add_library(utils STATIC utils.cpp)
target_include_directories(utils PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
