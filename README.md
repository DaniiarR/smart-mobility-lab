# smart-mobility-lab
Make a folder named "catkin_ws" to be used as a workspace for different projects.

Inside the "catkin_ws" folder, make another folder named "src" which will contain source code for projects.

To generate executables, libraries, and interfaces, run the command "catkin_make" inside the "catkin_ws" folder.

Whenever a new package is built, update the environment by running the command "source devel/setup.bash" in every new terminal tab. This adds various environment variables that ROS requires to function.

Inside the "src" folder, create a new folder for the project you are working on and create a sub-folder called "src" inside it.

Finally, go back to the "catkin_ws" folder and run "catkin_make" to build the project configuration.
