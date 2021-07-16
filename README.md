# udacity_myrobot

This repo contains the autor's solution to the projects proposed in the course [Robotics Software Engineer Nanodegree Program](https://www.udacity.com/course/robotics-software-engineer--nd209). The package is tested in ROS Kinect.

## Installation

Make sure you have the following packages installed

```
$ sudo apt-get install ros-kinetic-navigation
$ sudo apt-get install ros-kinetic-map-server
$ sudo apt-get install ros-kinetic-move-base
$ sudo apt-get install ros-kinetic-amcl
```

Clone the repositories and build it in your workspace folder /src

```
git clone https://github.com/ros-teleop/teleop_twist_keyboard
git clone https://github.com/jcorredorc/udacity_myrobot.git
```

## Usage


```
roslaunch my_robot world.launch
roslaunch my_robot amcl.launch
```

Now you could run the teleop script to test the localization via amcl package

```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

Or you can use the 2D Navigation Goal tool from Rviz


![GitHub Logo](/images/xdp_imagenUdacity_proj3.jpg)

