cmake_minimum_required(VERSION 3.18)

project(hello)

add_executable (hello)

target_sources (hello PRIVATE main.cpp)