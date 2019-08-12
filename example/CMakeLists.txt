project(NomadEcsExample)
cmake_minimum_required(VERSION 3.6)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)


include_directories("../src")
add_executable(nomadexample main.cpp)
target_link_libraries(nomadexample "nomadecs")
