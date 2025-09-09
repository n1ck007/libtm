cmake_minimum_required(VERSION 3.22)
project(tm)

set(CMAKE_CXX_STANDARD 20)
set(SOURCES src/tm.cpp)
include_directories(src lib/CmdParser)

add_executable(${PROJECT_NAME} ${SOURCES})
