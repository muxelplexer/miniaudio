cmake_minimum_required(VERSION 3.31)
project(miniaudio)
add_library(miniaudio INTERFACE)
target_include_directories(miniaudio INTERFACE
    .
)
