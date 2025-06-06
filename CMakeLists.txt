cmake_minimum_required(VERSION 3.15)
projet(TradeSandbox LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED true)

file(GLOB_RECURSE SRC_FILES src/*.cpp)

add_executable(TradeSandbox ${SRC_FILES})
