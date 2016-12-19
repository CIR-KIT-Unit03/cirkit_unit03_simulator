cmake_minimum_required(VERSION 2.8.3)
project(cirkit_unit03_gazebo)
find_package(catkin REQUIRED COMPONENTS roslaunch)

roslaunch_add_file_check(test/cirkit_unit03_clearpath_playpen_launch.test.xml)
roslaunch_add_file_check(test/cirkit_unit03_world_launch.test.xml)
roslaunch_add_file_check(test/description.gazebo_launch.test.xml)
