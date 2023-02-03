cmake_minimum_required(VERSION 3.0.2)
project(lidar_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch meshes rviz urdf world
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
