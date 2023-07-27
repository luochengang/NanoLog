cmake_minimum_required(VERSION 3.16)
project(Nanolog)

set(CMAKE_CXX_STANDARD 11)
include_directories(include)
aux_source_directory(src SRC_LIST)
add_executable(main ${SRC_LIST})
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)