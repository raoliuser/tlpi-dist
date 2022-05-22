# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(t_mount t_mount.c)
add_executable(t_umount t_umount.c)
add_executable(t_statfs t_statfs.c)
add_executable(t_statvfs t_statvfs.c)