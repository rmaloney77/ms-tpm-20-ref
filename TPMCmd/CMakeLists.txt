cmake_minimum_required (VERSION 3.1)
project(simulator)

#add_definitions(-DUSE_DEBUG_RNG=1)

include_directories(Platform/include)
include_directories(Platform/include/prototypes)

add_subdirectory(tpm)
add_subdirectory(Platform)
add_subdirectory(Simulator)
