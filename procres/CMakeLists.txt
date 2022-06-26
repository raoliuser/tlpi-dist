set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(rlimit_nproc rlimit_nproc.c)
add_executable(rusage rusage.c)
add_executable(rusage_wait rusage_wait.c)