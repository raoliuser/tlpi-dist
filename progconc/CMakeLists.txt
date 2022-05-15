# cmake_minimum_required(VERSION 3.20)

# add_definitions(-DNOSYSCALL) 
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR} SRC_LIST)
add_executable(syscall_speed ${SRC_LIST})