cmake_minimum_required(VERSION 3.31)
project(miniaudio)
add_library(miniaudio INTERFACE miniaudio.h)
target_include_directories(miniaudio INTERFACE
    .
)
