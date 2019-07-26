cmake_minimum_required(VERSION 3.10.0 FATAL_ERROR)
project(imgui)

set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS_REALEASE "-O3")

add_library(imgui STATIC
	imgui.cpp
	imgui_draw.cpp
	imgui_widgets.cpp
)
