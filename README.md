#### SLAM (simultaneous localization and mapping) is a technique used to create and build a map for a telecontrol of the robotics. 

In order to do that you need to download the turtlebot packages and follow some steps: 

#### 1 - Go to https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/ 

Choose your ROS version first. 

![](images/phonto.jpg)

#### 2 - Now open your terminal and write the following commands in order (in case you are using ROS noetic). 

![](images/remote.jpg)

####  Install ROS on Remote PC and write the follwoing commands: 
- $ sudo apt update
- $ sudo apt upgrade
- $ wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_noetic.sh
- $ chmod 755 ./install_ros_noetic.sh 
- $ bash ./install_ros_noetic.sh

#### Install Dependent ROS Packages: 
- $ sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \
  ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \
  ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \
  ros-noetic-rosserial-python ros-noetic-rosserial-client \
  ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \
  ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \
  ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \
  ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers

* Note: The above command is one full command, so copy the entire lines. 

#### Install TurtleBot3 Packages: 
- $ sudo apt install ros-noetic-dynamixel-sdk
- $ sudo apt install ros-noetic-turtlebot3-msgs
- $ sudo apt install ros-noetic-turtlebot3 

For the simulation packages go to: https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/ 
