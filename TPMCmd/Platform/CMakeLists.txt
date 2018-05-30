cmake_minimum_required (VERSION 3.1)

include_directories(include)
include_directories(include/prototypes)
include_directories(../tpm/include)
include_directories(../tpm/include/prototypes)

project(tpm_pform)
add_library(tpm_pform "")
set_target_properties(tpm_pform PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")

add_subdirectory(src)
