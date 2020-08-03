# Udacity course project 05: Map my World  
Udacity robotics course: Project 05 Map my world

Overview:
this project goal is to create a 2D occupancy grid and 3D octomap from a simulated environment using your own robot with the RTAB-Map package.

RTAB-Map (Real-Time Appearance-Based Mapping) is a popular solution for SLAM to develop robots that can map environments in 3D. RTAB-Map has good speed and memory management, and it provides custom developed tools for information analysis. 

For this project we will be using the rtabmap_ros package, which is a ROS wrapper (API) for interacting with RTAB-Map. Keep this in mind when looking at the relative documentation.

Links:
* ROS Wiki (http://wiki.ros.org/rtabmap_ros). 

This project tasks: 
1. You will develop your own package to interface with the rtabmap_ros package.
2.  You will build upon your localization project to make the necessary changes to interface the robot with RTAB-Map. An example of this is the addition of an RGB-D camera.
3. You will ensure that all files are in the appropriate places, all links are properly connected, naming is properly setup and topics are correctly mapped. Furthermore you will need to generate the appropriate launch files to launch the robot and map its surrounding environment.
4. When your robot is launched you will teleop around the room to generate a proper map of the environment.

