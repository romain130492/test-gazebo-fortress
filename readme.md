

## Description


rosdep install --from-paths src --ignore-src -r -y

colcon build --symlink-install

source install/setup.bash

ros2 launch my_robot_bringup my_robot_gazebo.launch.xml









## Gazebo ignition fortress

- create an empty world : https://github.com/turtlebot/TurtleBot4Lessons/blob/main/units/Unit01-ROS-2-Basics/L02-Gazebo-World/U01-L02-Empty-World.md
  - To check further that course above.


- launch gazebo fortress: `ign gazebo -v 4`
  - v for verbose and level of verbose


- worlds: https://github.com/osrf/gazebo_models






SolidWorks