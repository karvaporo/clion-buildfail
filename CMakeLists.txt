project(clion-buildfail)
cmake_minimum_required(VERSION 3.3)

find_package(Qt5Gui)

add_executable(clion-buildfail main.cpp)

target_link_libraries(clion-buildfail Qt5::Gui)