cmake_minimum_required(VERSION 3.26)
project(RTChat)

include(cmake/CPM.cmake)
include(cmake/json.cmake)
include(cmake/spdlog.cmake)

set(CMAKE_CXX_STANDARD 17)

add_executable(rt-chat-exe main.cpp)
