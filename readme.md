rosdep install --from-paths src --ignore-src -r -y

colcon build --symlink-install

source install/setup.bash

ros2 launch my_robot_bringup my_robot_gazebo.launch.xml