# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(daemon_SIGHUP daemon_SIGHUP.c)
add_executable(test_become_daemon test_become_daemon.c)
add_executable(t_syslog t_syslog.c)