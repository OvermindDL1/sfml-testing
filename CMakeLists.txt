cmake_minimum_required(VERSION 3.11)

project(sfml-testing)


add_subdirectory(SFML)

add_executable(sfml-testing main.cpp)

target_link_libraries(sfml-testing sfml-graphics)

