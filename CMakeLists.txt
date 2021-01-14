cmake_minimum_required(VERSION 3.5)

project(Simple-Vulkan LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(vulkan REQUIRED)

add_executable(Simple-Vulkan main.cpp)
target_link_libraries(Simple-Vulkan Vulkan::Vulkan)
