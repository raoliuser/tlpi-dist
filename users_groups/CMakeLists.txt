set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(t_getpwnam_r t_getpwnam_r.c)
add_executable(t_getpwent t_getpwent.c)
add_executable(check_password check_password.c)
target_link_libraries(check_password crypt) 