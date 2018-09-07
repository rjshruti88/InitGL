cmake_minimum_required(VERSION 3.1)

set(GLAD_DIR "${CMAKE_CURRENT_SOURCE_DIR}")
set(GLAD_DIR ${GLAD_DIR} PARENT_SCOPE)

add_library("glad" "${GLAD_DIR}/src/glad.c")
