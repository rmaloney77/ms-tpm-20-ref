cmake_minimum_required (VERSION 3.1)

#TODO: Make this conditional to account for wolfssl and ltc
#target_compile_definitions(tpm PRIVATE MATH_LIB=OSSL)
#target_compile_definitions(tpm PRIVATE MATHLIB=OSSL)
#target_compile_definitions(tpm PRIVATE SYM_LIB=OSSL)
#target_compile_definitions(tpm PRIVATE HASH_LIB=OSSL)
find_package(OpenSSL REQUIRED)
include_directories(${OPENSSL_INCLUDE_DIR})
include_directories(include/ossl)

include_directories(include)
include_directories(include/prototypes)
include_directories(include-ext)

project(tpm)
add_library(tpm "")
set_target_properties(tpm PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")

add_subdirectory(src)

target_link_libraries(tpm ${OPENSSL_LIBRARIES})
