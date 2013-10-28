cmake_minimum_required(VERSION 2.8.3)
project(LMS1xx)	

#Find catkin and any catkin packages
find_package(catkin REQUIRED COMPONENTS roscpp std_msgs sensor_msgs genmsg)

#Declare a catkin package
catkin_package()

#Find executables
add_executable(LMS100 src/LMS1xx_node.cpp)
add_executable(set_config src/setConfig.cpp)

