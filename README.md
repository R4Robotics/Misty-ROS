# Misty-ROS
This is a ROS bridge for Misty robot by Misty Robotics. You can test your scripts that you have created for misty using this URDF file for the simulation.

## Set Up
1. Have a working installation of ROS-Noetic set up on your Ubunto OS (Instructions on how to do this can be found on the ROS wiki)
2. Clone the misty_description folder to your catkin workspace. 
3. Use ```catkin_make``` and ```source devel/setup.bash``` to build the project.
4. Launch the gazebo file to simulate misty

## How It Works
The misty_description folder has three major folders. The meshses and the URDF folder contains all the information that the simulation needs to create a virtual version of Misty. The launch files are what you will use to start your program. The two launch files you will use the most are the gazebo and rviz files. 

Launch the gazebo file using ```roslaunch misty_description gazebo.launch```.

Launch the rviz file using ```roslaunch misty_description display.launch```.

If everything worked, after launching the gazebo file, misty should appear at the origin like in the image below.
![Misty_in_Gazebo](https://user-images.githubusercontent.com/78620821/117919480-3ab7f780-b32c-11eb-9ca5-b9be01b4e43b.PNG "Misty in Gazebo")

For any errors contact us at support@r4robotics.com.au

Now you're ready to start making some scripts to program misty!
