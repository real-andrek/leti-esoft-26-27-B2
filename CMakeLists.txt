cmake_minimum_required(VERSION 3.20)
project(leti-esoft-26-27-B2)
set(CMAKE_CXX_STANDARD 17)

add_executable(leti-esoft-26-27-B2 main.cpp)

include_directories(Core)
add_subdirectory(Core)
add_subdirectory(CoreTests)
add_subdirectory(ConsoleApp)

target_link_libraries(leti-esoft-26-27-B2 Core)