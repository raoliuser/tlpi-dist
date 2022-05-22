set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

link_libraries(acl)
add_executable(acl_view acl_view.c)
add_executable(acl_update acl_update.c)