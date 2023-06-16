cmake_minimum_required(VERSION 3.0.0)
project(hri_actions_msgs)

find_package(catkin REQUIRED COMPONENTS
  message_generation
  actionlib_msgs
  geometry_msgs
)

add_message_files(
    DIRECTORY msg
    FILES
    LookAtWithStyle.msg
    Intent.msg
)

add_action_files(
  DIRECTORY action
  FILES
    LookAt.action
    PointTrajectory.action
    ApplicationControl.action
)
generate_messages(
    DEPENDENCIES
    actionlib_msgs
    geometry_msgs
)

catkin_package(
    CATKIN_DEPENDS 
    geometry_msgs
    actionlib_msgs
)


