cmake_minimum_required(VERSION 3.10)
project(panning
    VERSION 0.0.1
    DESCRIPTION "a demo of cmake panning"
    HOMEPAGE_URL "https://github.com/Flovers/cmake_panning_demo"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)

# 设置变量
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)
set(Process_Dir ${CMAKE_SOURCE_DIR}/src/process)
set(PNC_Map_Dir ${CMAKE_SOURCE_DIR}/src/pnc_map)
# 添加子目录
add_subdirectory(src)