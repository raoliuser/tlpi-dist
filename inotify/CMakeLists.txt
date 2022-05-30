# cmake_minimum_required(VERSION 3.20)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(demo_inotify demo_inotify.c)
add_executable(dnotify dnotify.c)
add_executable(inotify_dtree inotify_dtree.c)
add_executable(rand_dtree rand_dtree.c)