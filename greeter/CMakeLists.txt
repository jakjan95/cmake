cmake_minimum_required(VERSION 3.10)
project(greeter)

set(CMAKE_CXX_STANDARD 17)
set(FILES main.cpp greeter.cpp person.cpp)
add_executable(${PROJECT_NAME} ${FILES})
