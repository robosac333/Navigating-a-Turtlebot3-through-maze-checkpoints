# Navigating-a-Turtlebot3-through-maze-checkpoints
This was the Final Project of Robotics Programming using C++ course (ENPM809Y)
This assignment consisted of the following steps:

– Create a map of the environment (already provided).

– Load the generated map (already performed).

– Read one ArUCo marker and retrieve the appropriate parameters.

– Detect parts using logical cameras.

– Write an action client to go through each part using the order described by
the parameters.

Setup and Installation
• ArUco marker detection requires the latest version of OpenCV.

– pip3 uninstall opencv-python

– pip3 uninstall opencv-contrib-python

– pip3 install opencv-contrib-python

• To install ROS packages for this assignment, it is recommended to create a newworkspace.

– cd

– mkdir -p ~/final_ws/src

– cd final_ws

- place the package from this repository in the src folder

– colcon build

Launch the simualation mize by running the following command
ros2 launch final_project final_project.launch.py

run the script node using
ros2 run lecture12 navigator_23

![image](https://github.com/robosac333/Navigating-a-Turtlebot3-through-maze-checkpoints/assets/143353582/b2aa7e34-99dc-4b5d-8590-c761f3359de5)


To solve any other issue with loading the simulation and script refer the Problem Statement
