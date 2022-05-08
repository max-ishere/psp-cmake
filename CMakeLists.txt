cmake_minimum_required(VERSION 3.10)

project(psp-cmake
  VERSION 0.0
  DESCRIPTION "CMake PSP template project"
  HOMEPAGE_URL "github.com/max-ishere/psp-cmake"
  LANGUAGES CXX)

include_directories(include)
add_subdirectory(src)
