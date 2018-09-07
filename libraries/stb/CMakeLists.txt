cmake_minimum_required(VERSION 3.1)

set(STB_DIR "${CMAKE_CURRENT_SOURCE_DIR}")
set(STB_DIR ${STB_DIR} PARENT_SCOPE)

add_library("stb" "${STB_DIR}/src/stb_image.c")
