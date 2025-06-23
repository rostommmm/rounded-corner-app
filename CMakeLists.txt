cmake_minimum_required(VERSION 3.5)
project(RoundedCornerApp)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_AUTOMOC ON)

find_package(Qt5 COMPONENTS Widgets REQUIRED)

add_executable(RoundedCornerApp src/main.cpp src/RoundedWindow.cpp)

target_link_libraries(RoundedCornerApp Qt5::Widgets)
