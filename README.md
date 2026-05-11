### Requirements

- ROS2 Jazzy
- Gazebo
- RViz2
- Python 3.12 or newer
- `ros_gz_bridge`
- `robot_state_publisher`
- `joint_state_publisher`

### Build & Run

1. Clone Repository

       git clone https://github.com/ichsanyudika12/re402-ros2-midterm.git
       cd re402-ros2-midterm

2. Build Workspace

       colcon build

3. Source Workspace

       source install/setup.bash

4. Launch Simulation

       ros2 launch my_robot robot_launch.py

### Features

- Mobile robot simulation in Gazebo
- Robot visualization using RViz2
- IMU sensor integration
- ROS2 topic communication
