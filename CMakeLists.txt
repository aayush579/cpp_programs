cmake_minimum_required(VERSION 4.1)
project(newcpp)

set(CMAKE_CXX_STANDARD 20)

add_executable(newcpp pattern_reverse_no.cpp
        count_pattern.cpp
        triangle_pattern.cpp
        same_number_triangle.cpp
        count_triangular.cpp
        reverse_count_triangula.cpp
        alphabet_pattern.cpp
        "count_alphabet.cpp"
        asterisk_pattern.cpp)
