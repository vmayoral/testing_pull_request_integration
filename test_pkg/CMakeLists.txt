cmake_minimum_required(VERSION 2.8.3)
project(test_pkg)

find_package(catkin REQUIRED)

catkin_package()

if(CATKIN_ENABLE_TESTING)
  catkin_add_nosetests(test)
endif()
