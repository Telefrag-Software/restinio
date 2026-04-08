cmake_minimum_required(VERSION 3.14)

option(HUNTER_ENABLED "Enable Hunter package manager support" ON)

include(dev/cmake/hunter/HunterInit.cmake)

project(restinio-wrapper)

add_subdirectory(dev)
