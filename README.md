# ros2_examples

## Overview
Some ROS examples to practice

## TOC
1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Example Usage 1](#example-usage-1)
5. [Example Usage 2](#example-usage-2)
6. [Bugs, feature requests, etc](#bugs-feature-requests-etc)

## Requirements
- ROS Humble Desktop installation on Ubuntu
- Colcon install: 'sudo apt install python3-colcon-common-extensions'

## Configuration
0. Configurate the '.bashrc': 'echo "source /opt/ros/humble/setup.bash" >> ~/.bashrc'
1. Create catkin workspace: 'mkdir -p ~/ros2_ws/src'
2. In the '~/ros2_ws' folder run 'colcon build'
3. Configurate the '.bashrc': 'echo "source ~/ros2_ws/install/setup.bash" >> ~/.bashrc'
4. Reopen the terminal or run 'source .bashrc'
4. Clone the repository in the '~' folder ('/home/user')

## Creating a ROS 2 Python Package
1. Go to the 'cd ~/ros2_ws/src' folder
2. In the src folder run the 'ros2 pkg create --build-type ament_python my_package_name'
3. Go to the 'cd ~/ros2_ws' folder
4. Run 'colcon build'
5. Optional: source the local overlay: '. install/local_setup.bash'
