cmake_minimum_required(VERSION 3.20.0)
project(
    planning
    VERSION 0.0.1
    DESCRIPTION "a demo of cmake planning"
    HOMEPAGE_URL "https://github.com/yyyyyh21/CMake_planning_demo"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
set(Process_Dir ${PROJECT_SOURCE_DIR}/src/process)
set(Pnc_Map_Dir ${PROJECT_SOURCE_DIR}/src/pnc_map)

add_subdirectory(src) #添加子目录
