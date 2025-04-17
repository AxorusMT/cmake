cmake_minimum_required(VERSION 3.21)

project(DemoProject)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include(cmake/CPM.cmake)

# Add packages using the format below:
# CPMAddPackage("gh:libsdl-org/SDL#release-3.2.4")
# CPMAddPackage("gh:wolfpld/tracy@0.11.1")

add_executable(TauEngine ${CMAKE_CURRENT_SOURCE_DIR}/Source/main.cpp)
