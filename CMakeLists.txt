cmake_minimum_required(VERSION 3.19)

project(hello)

add_executable (hello)

target_sources (hello PRIVATE main.cpp)