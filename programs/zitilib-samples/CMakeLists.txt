
add_executable(zitilib-server server.c)
target_link_libraries(zitilib-server PUBLIC ziti)

#add_executable(forky forky-client.c)
#target_link_libraries(forky PUBLIC ziti)