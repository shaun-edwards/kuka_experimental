# Kuka KR10 Gazebo

##Overview

This package contains the files required to simulate the KR10  manipulator (and variants) in Gazebo.


## Using Moveit! with Gazebo Simulator

1. Bring the robot model into gazebo and load the ros_control controllers:
   ```roslaunch kuka_kr10_gazebo kr10_gazebo.launch```

2. Launch moveit! and ensure that it is configured to run alongside Gazebo:
```roslaunch kuka_kr10_moveit_config moveit_planning_execution_gazebo.launch```



**Notes:**

1. If running with ROS Hydro, transmission elements will need to be modified as discussed in [ros-industrial/universal_robot#179][].

[ros-industrial/universal_robot#179]: https://github.com/ros-industrial/universal_robot/pull/179
