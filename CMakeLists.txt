project(hello CXX)
cmake_minimum_required(VERSION 2.8)
#aux_source_directory(. SRC_LIST)
set(${PROJECT_NAME}_SRC
src/main.cpp
)
add_executable(${PROJECT_NAME} ${${PROJECT_NAME}_SRC})

