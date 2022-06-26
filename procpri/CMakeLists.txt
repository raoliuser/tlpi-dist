set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(t_setpriority t_setpriority.c)
add_executable(sched_set sched_set.c)
add_executable(sched_view sched_view.c)
add_executable(t_sched_getaffinity t_sched_getaffinity.c)
add_executable(t_sched_setaffinity t_sched_setaffinity.c)
add_executable(demo_sched_fifo demo_sched_fifo.c)