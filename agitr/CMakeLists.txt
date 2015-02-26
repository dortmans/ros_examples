# What version of CMake is needed?
cmake_minimum_required(VERSION 2.8.3)

# The name of this package.
project(agitr)

# Find the catkin build system, and any other packages on which we depend.
find_package(catkin REQUIRED COMPONENTS roscpp geometry_msgs turtlesim std_srvs)

# Declare our catkin package.
catkin_package()

# Specify locations of header files.
include_directories(include ${catkin_INCLUDE_DIRS})

# Declare the executable, along with its source files.
add_executable(hello src/hello.cpp)
add_executable(pubvel src/pubvel.cpp)
add_executable(subpose src/subpose.cpp)
add_executable(count src/count.cpp)
add_executable(once src/once.cpp)
add_executable(throttle src/throttle.cpp)
add_executable(reverse_cmd_vel src/reverse_cmd_vel.cpp)
add_executable(set_bg_color src/set_bg_color.cpp)
add_executable(pubvel_with_max src/pubvel_with_max.cpp)
add_executable(spawn_turtle src/spawn_turtle.cpp)
add_executable(pubvel_toggle src/pubvel_toggle.cpp)
add_executable(anon src/anon.cpp)

# Specify libraries against which to link.
target_link_libraries(hello ${catkin_LIBRARIES})
target_link_libraries(pubvel ${catkin_LIBRARIES})
target_link_libraries(subpose ${catkin_LIBRARIES})
target_link_libraries(count ${catkin_LIBRARIES})
target_link_libraries(once ${catkin_LIBRARIES})
target_link_libraries(throttle ${catkin_LIBRARIES})
target_link_libraries(reverse_cmd_vel ${catkin_LIBRARIES})
target_link_libraries(set_bg_color ${catkin_LIBRARIES})
target_link_libraries(pubvel_with_max ${catkin_LIBRARIES})
target_link_libraries(spawn_turtle ${catkin_LIBRARIES})
target_link_libraries(pubvel_toggle ${catkin_LIBRARIES})
target_link_libraries(anon ${catkin_LIBRARIES})

