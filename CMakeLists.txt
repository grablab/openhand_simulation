cmake_minimum_required(VERSION 2.8.3)
project(openhand_simulator)

find_package(catkin REQUIRED)

catkin_package()


install(DIRECTORY launch model_o t42
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
