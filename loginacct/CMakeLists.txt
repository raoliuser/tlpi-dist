# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(dump_utmpx dump_utmpx.c)
add_executable(utmpx_login utmpx_login.c)
add_executable(view_lastlog view_lastlog.c)