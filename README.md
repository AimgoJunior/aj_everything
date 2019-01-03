### Amigo Junior
#### Experiment indoor mapping
This repository contains everything that runs on the Turtlebot3 Burger.

#### Getting Started
##### Dual-booting your computer
We use Ubuntu 16.04 LTS. 
##### Installing ROS
We use ROS Kinetic. Follow the [ROS Setup Guide](http://wiki.ros.org/kinetic/Installation/Ubuntu).
##### Clone this repository and configure dependencies
Run the following commands to setup this repo:
```bash
sudo apt-get update

cd catkin_ws
rosdep update && rosdep install -r -y -i --from-paths src --rosdistro kinetic

catkin_make
```

