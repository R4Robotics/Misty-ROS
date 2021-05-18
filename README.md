# Misty-ROS
This is a ROS bridge for Misty robot by Misty Robotics. You can test your scripts that you have created for misty using this URDF file for the simulation.

## Set Up
1. Download the misty_description folder, containing the launch files, meshes, and URDF file. 
2. Extract the folder to your workspace.
3. Run catkin_make and source.

## How It Works
The launch files can be used to simulate Misty in Gazebo and Rviz. 

Launch the gazebo file using ```roslaunch misty_description gazebo.launch```.

Launch the rviz file using ```roslaunch misty_description display.launch```.

If everything worked, after launching the gazebo file, misty should appear at the origin like in the image below.
![Misty_in_Gazebo](https://user-images.githubusercontent.com/78620821/117919480-3ab7f780-b32c-11eb-9ca5-b9be01b4e43b.PNG "Misty in Gazebo")


