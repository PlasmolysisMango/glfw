cmake_minimum_required(VERSION 3.0.0)

project(glfw)

add_definitions(-DNOMINMAX)

find_package(pxr REQUIRED)

include_directories("C:/Users/Jack/AppData/Local/Programs/Python/Python39/include")

add_executable(glfw main.cpp glad.c)

target_link_libraries(glfw usd usdImagingGL)

include_directories("D:/Program Files/glfw-3.3.7.bin.WIN64/include")

target_link_libraries(glfw "D:/Program Files/glfw-3.3.7.bin.WIN64/lib-vc2019/glfw3.lib")

include_directories("D:/Program Files/glad/include")





