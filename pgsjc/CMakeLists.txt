# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(t_setsid t_setsid.c)
add_executable(catch_SIGHUP catch_SIGHUP.c)
add_executable(disc_SIGHUP disc_SIGHUP.c)
add_executable(job_mon job_mon.c)