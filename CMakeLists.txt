cmake_minimum_required(VERSION 3.15.0)
project(opengl-with-conan)
set(CMAKE_EXPORT_COMPILE_COMMANDS on)

add_definitions("-std=c++17")

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(rov src/main.cpp)
target_link_libraries(rov ${CONAN_LIBS})


