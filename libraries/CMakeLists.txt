cmake_minimum_required(VERSION 3.1)

set(LIB_DIR ${CMAKE_CURRENT_SOURCE_DIR})
set(LIB_DIR ${LIB_DIR} PARENT_SCOPE)

# GLFW
set(GLFW_DIR "${LIB_DIR}/glfw")
set(GLFW_DIR ${GLFW_DIR} PARENT_SCOPE)
set(GLFW_BUILD_EXAMPLES OFF CACHE INTERNAL "Build the GLFW example programs")
set(GLFW_BUILD_TESTS OFF CACHE INTERNAL "Build the GLFW test programs")
set(GLFW_BUILD_DOCS OFF CACHE INTERNAL "Build the GLFW documentation")
set(GLFW_INSTALL OFF CACHE INTERNAL "Generate installation target")
