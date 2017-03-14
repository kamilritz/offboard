cmake_minimum_required(VERSION 2.8.3)
project(offboard)

find_package(catkin_simple REQUIRED)

catkin_simple()

cs_add_executable(offboard src/offb_node.cpp)

cs_install()


cs_export()
