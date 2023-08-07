# turtlebot3
Scan a region with turtlebot3.
#Install Dependent ROS Packages ( 
$ sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \ ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \ ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \ ros-noetic-rosserial-python ros-noetic-rosserial-client \ ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \ ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \ ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \ ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers
## secondly Install TurtleBot3 Packages
Install TurtleBot3 via Debian Packages.
$ sudo apt install ros-noetic-dynamixel-sdk
$ sudo apt install ros-noetic-turtlebot3-msgs
$ sudo apt install ros-noetic-turtlebot3
## Download the source codes.
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/src/
$ git clone -b noetic-devel https://github.com/ROBOTIS-GIT/DynamixelSDK.git
$ git clone -b noetic-devel https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git
$ git clone -b noetic-devel https://github.com/ROBOTIS-GIT/turtlebot3.git
$ cd ~/catkin_ws && catkin_make
# Started 
## run Gazebo
to open Gazebo and see the place.
![Gazebo](https://github.com/ns-c1/turtlebot3/assets/139014871/b2a2134d-f789-4523-822a-0c1cdaa01554)
## run turtlebot3_slam
to open turtlebot3_slam and see the scan place.
![turtlebot3_slam](https://github.com/ns-c1/turtlebot3/assets/139014871/6a0b2fbd-50fb-4953-832e-c4cfa8236394)
## Control tool
Robot control tool.
The movement of the robot is controlled via the keyboard using the letters W A S D X
![turtlebot3_teleop_kay](https://github.com/ns-c1/turtlebot3/assets/139014871/9288c212-4162-44bf-af66-b7f7b68d89d6)
## Scan result
The final map of the csan process area.
![Scan result](https://github.com/ns-c1/turtlebot3/assets/139014871/21cef593-ffe7-4a45-b775-37c69a29ed0e)
