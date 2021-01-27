cmake_minimum_required(VERSION 3.15)
project(Adafruit_ADS1X15)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Adafruit_ADS1X15
        Adafruit_ADS1015.cpp
        Adafruit_ADS1015.h
        library.properties)
