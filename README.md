# cassie_description
This repository contains the UDRF model of the CASSIE robot (with no springs) from Agility Robotics. 
It also includes a a way to visualize the robot using ROS and rviz. 


Installation to view .urdf using rviz
=====================================

- Download and install ROS by following the instructions at http://wiki.ros.org/indigo/Installation/Ubuntu.

- Create a folder for the catkin workspace 
```
mkdir ~/catkin_ws
cd ~/catkin_ws
mkdir src
cd src
catkin_init_workspace
```
- Clone the repository to get the cassie_description package
```
git clone https://github.com/UMich-BipedLab/cassie_description.git
```
- Build the package
```
cd ../
catkin_make
source devel/setup.bash
```
- Launch rviz to visualize the .urdf file
```
roslaunch cassie_description display.launch 
```

