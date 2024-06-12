cmake_minimum_required(VERSION 3.28)
project(ADS_P2_1_Sortieren)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ADS_P2_1_Sortieren
        catch.h
        main.cpp
        sorting.cpp
        sorting.h
        unit_tests.cpp)
