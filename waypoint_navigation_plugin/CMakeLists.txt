cmake_minimum_required(VERSION 3.8)
project(waypoint_navigation_plugin)

find_package(catkin QUIET COMPONENTS roscpp)
find_package(ament_cmake QUIET)
include(${CMAKE_CURRENT_SOURCE_DIR}/cmake/ROS2.cmake)
