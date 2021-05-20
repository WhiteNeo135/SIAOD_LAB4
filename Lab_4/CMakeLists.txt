cmake_minimum_required(VERSION 3.17)
project(Lab_4)

set(CMAKE_CXX_STANDARD 17)

add_executable(Lab_4 main.cpp test.cpp)

get_filename_component(DATA_PATH ${CMAKE_SOURCE_DIR}/input_output_files/ ABSOLUTE)
add_compile_definitions(DATA_PATH=\"${DATA_PATH}\")