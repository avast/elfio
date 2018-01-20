cmake_minimum_required(VERSION 3.6)

project(elfio CXX)

add_library(elfio INTERFACE)
target_include_directories(elfio SYSTEM INTERFACE "${PROJECT_SOURCE_DIR}/include")
