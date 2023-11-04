cmake_minimum_required(VERSION 3.27)
project(Starter)

set(CMAKE_CXX_STANDARD 17)

enable_testing()

set(SOURCE_FILES
        main.cpp
)
add_executable(Starter ${SOURCE_FILES})
add_subdirectory(tests)
