cmake_minimum_required(VERSION 3.10...3.21)

project(ufo-esp32
  VERSION
    1.0
  DESCRIPTION
    "Dynatrace Ufo project"
  LANGUAGES
    CXX
)

add_executable (ufo-esp32-bin Ufo.cpp)
