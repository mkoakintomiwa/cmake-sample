cmake_minimum_required(VERSION 3.16)

add_executable(main main.cpp)

find_package(json-c CONFIG REQUIRED)
target_link_libraries(main PRIVATE json-c::json-c)