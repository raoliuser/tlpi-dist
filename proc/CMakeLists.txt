# cmake_minimum_required(VERSION 3.20)

# add_definitions(-DNOSYSCALL) 
add_definitions(-DTEST_IT) 

# add_compile_options(-Wall -Wextra -O0)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(mem_segments mem_segments.c)
add_executable(necho necho.c)
add_executable(display_env display_env.c)
add_executable(modify_env modify_env.c)
add_executable(t_getenv t_getenv.c)
add_executable(setenv setenv.c)
add_executable(longjmp longjmp.c)
add_executable(bad_longjmp bad_longjmp.c)
add_executable(setjmp_vars setjmp_vars.c)