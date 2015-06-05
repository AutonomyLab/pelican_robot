cmake_minimum_required(VERSION 2.8.3)
project(pelican_base)

find_package(catkin REQUIRED roslaunch)

# catkin_python_setup()

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES pelican_base
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

## Mark other files for installation (e.g. launch and bag files, etc.)
# install(FILES
#   # myfile1
#   # myfile2
#   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )
roslaunch_add_file_check(launch)
