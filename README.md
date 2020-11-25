Teleoperation of the Covid Light Robot v 1.0

Add the following lines to your .bashrc

export ROS_MASTER_URI=http://192.168.64.100:11311
export ROS_IP=192.168.64.120

Set your wifi board IP address:

IP Address:	192.168.64.120
Subnet Mask:	255.255.192.0
Gateway:	192.168.64.3

Make sure that you installed Joy package on this PC.

Execute launch files on Master Node (Robot) as indicated in README.md of DiffWheel_Robot_Control Package

Open Terminal and type:

roslaunch lighteleop starteleop.launch


To be implemented: abstraction of the joy input.
