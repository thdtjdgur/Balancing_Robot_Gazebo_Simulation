cmake_minimum_required(VERSION 3.8)
project(hanium)
find_package(ament_cmake REQUIRED)
install(DIRECTORY urdf balancing_robot_mesh launch rviz
  DESTINATION share/${PROJECT_NAME})
ament_package()
