cmake_minimum_required(VERSION 2.8.6)
project(common_headers)

find_package(catkin REQUIRED)

catkin_package(
   INCLUDE_DIRS include)
   
install(DIRECTORY include/${PROJECT_NAME}/
  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
)
