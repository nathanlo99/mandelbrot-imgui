cmake_minimum_required(VERSION 3.16.3)

project(imgui-cmake LANGUAGES C CXX)

set (CMAKE_CXX_STANDARD 17)

# Use OpenGLES instead of OpenGL.
#set(USE_GLES ON)

add_subdirectory("libs")
add_subdirectory("src")
