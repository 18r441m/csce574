# Assignment 1

## Tested on Ubuntu 20.04 ROS noetic ✅

## Stage Tutorials
### Simulating One Robot in Stage - Instructions

- Install teleop package
`sudo apt-get install ros-noetic-teleop-twist-keyboard`

- Run roscore
`roscore`

- Lanuch stage
`rosrun stage_ros stageros $(rospack find stage_ros)/world/willow-erratic.world`

- Launch teleop keyboard
`rosrun teleop_twist_keyboard teleop_twist_keyboard.py`

- Visualize sensor data
``rosrun rviz rviz -d `rospack find stage_ros`/rviz/stage.rviz``
