1. project 3 phase 5 submission for group 18. (Team members: Akash Agarwal, Preyash Parikh, Ajinkya Parwekar)

2. The workspace name is ws_toycar.

3. To run the launch file for LiDAR sensor, run the command roslaunch toycar gazebo.launch

4. We have setup the LiDAR sensor (green colored) on the car according to the parameters given in the document.
	(The max angle is set to 1.57 and not 157)

5. The respective .yaml files and .py files for control part are included in the config and script folders respectievly.
	Also, the required additions are done in launch file and urdf file.

6. A seperate launch file named robot_position_controller.launch is created for control part.

7. To run the launch file for control part, run the command roslaunch toycar robot_position_controller.launch
