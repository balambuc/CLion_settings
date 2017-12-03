set(CMAKE_CXX_STANDARD 11)

add_library(src STATIC
        main.cpp)

target_include_directories(src PUBLIC headers)