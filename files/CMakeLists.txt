# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(t_stat t_stat.c file_perms.c)
add_executable(t_chown t_chown.c)
add_executable(t_umask t_umask.c)
add_executable(t_utime t_utime.c)
add_executable(t_utimes t_utimes.c)
add_executable(chiflag chiflag.c)