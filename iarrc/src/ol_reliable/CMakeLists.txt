add_executable(ol_reliable ol_reliable.cpp)
target_link_libraries(ol_reliable ${catkin_LIBRARIES})
add_dependencies(ol_reliable rr_platform_generate_messages_cpp)
