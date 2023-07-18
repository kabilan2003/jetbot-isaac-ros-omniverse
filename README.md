# JetBot Isaac ROS Omniverse Simulation

![Untitled design](https://github.com/kabilan2003/jetbot-isaac-ros-omniverse/assets/109456728/cac3d2bd-397f-484d-8b4c-a8824636f26d)

This repository contains ROS packages and configuration files to simulate the JetBot robot using NVIDIA Isaac and Omniverse technologies. The simulation environment allows for teleoperation, camera interface, and configuration of the JetBot robot within the Omniverse simulation platform.

# Prerequisites

Before running the JetBot simulation, you need to have the following software installed:
1. ubuntu20.04
2. ros noetic
3. isaac ros omniverse

# Launch isaac ros omniverse with jetbot from nvidia robot examples in create 

![image](https://github.com/kabilan2003/jetbot-isaac-ros-omniverse/assets/109456728/60f71eca-9b04-42a9-bfd6-a2c3734d5c7b)

# Add omni graph to jetbot 
Open Visual Scripting: Window > Visual Scripting > Action Graph.

![image](https://github.com/kabilan2003/jetbot-isaac-ros-omniverse/assets/109456728/76d70509-7a08-4ff6-ba9f-270882987bca)

The ROS1 Camera Helper is a versatile utility designed to streamline camera-related tasks within the Robot Operating System (ROS) environment. This package simplifies the process of publishing camera data by indicating the type of data to publish and the corresponding ROS topic for publication.

After connecting omni graph node 

# enable ros bridge 

ros bridge is used for connecting non ros program 

Window > extension > ros_bridge 

# configure omniverse isaac ros with ros 

run roscore on terrminal 
# And than run rqt graph on termanil 

for visualize the image from isaac ros omniverse 

#  Add tf-Transform for jetbot 










