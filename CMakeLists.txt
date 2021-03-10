cmake_minimum_required(VERSION 3.18)

add_library(FastNoiseLite INTERFACE )

target_include_directories(FastNoiseLite 
    INTERFACE Cpp/
)

add_library(Farscape::FastNoiseLite ALIAS FastNoiseLite)