set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

link_libraries(rt pthread)
add_executable(real_timer real_timer.c)
add_executable(timed_read timed_read.c)
add_executable(t_nanosleep t_nanosleep.c)
add_executable(t_clock_nanosleep t_clock_nanosleep.c) 
add_executable(ptmr_null_evp ptmr_null_evp.c)
add_executable(ptmr_sigev_signal ptmr_sigev_signal.c)
add_executable(ptmr_sigev_thread ptmr_sigev_thread.c)
add_executable(demo_timerfd demo_timerfd.c)
add_executable(cpu_burner cpu_burner.c)
add_executable(cpu_multi_burner cpu_multi_burner.c)
add_executable(cpu_multithread_burner cpu_multithread_burner.c)