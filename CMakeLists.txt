cmake_minimum_required(VERSION 3.1)

# Shared libs
add_subdirectory(libraries)
add_subdirectory(libraries/glfw)
add_subdirectory(libraries/glad)
add_subdirectory(libraries/stb)

# Executables
add_subdirectory(helloTriangle)
add_subdirectory(helloRectangle)
