cmake_minimum_required(VERSION 3.8)
project(MINT64)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.c)

add_custom_target(MINT64 ALL COMMAND make -C ${MINT64_SOURCE_DIR}
        CLION_EXE_DIR=${PROJECT_BINARY_DIR})