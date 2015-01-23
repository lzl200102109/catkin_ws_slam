# catkin_ws_slam

## Install

```
# install dependency packages
sudo apt-get install freeglut3-dev
sudo apt-get install liblapack-dev

# install mavlink
sudo apt-get install ros-indigo-mavlink

# install usbcam
sudo apt-get install ros-indigo-usb-cam

# add the workspace to ros package path
export ROS_PACKAGE_PATH=/home/catkin_ws_slam/src:$ROS_PACKAGE_PATH

# source this workspace
source ~/catkin_ws_slam/devel/setup.sh

source ~/.bashrc
```

## Usage

```
cd ~/catkin_ws_slam/launch

# start camera for adjusting shutter
roslauch camera.lauch

# launch svo
roslaunch svo_ros_atan.launch

# launch rviz
rviz

```
