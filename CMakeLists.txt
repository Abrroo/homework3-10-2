cmake_minimum_required(VERSION 3.19.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)
project(homework3-10-2)

add_library(classes Figure.cpp Triangle.cpp Quadrangle.cpp Equil_triangle.cpp Iso_triangle.cpp Right_triangle.cpp Parallelogram.cpp Rectangle.cpp Rhombus.cpp Square.cpp)



add_executable(homework3-10-2 homework3-6-3.cpp)

target_link_libraries(homework3-10-2 classes)
