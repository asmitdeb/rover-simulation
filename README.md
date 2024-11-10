
# Setup
Packages required: urdf_tutorial
 `sudo apt install ros-humble-urdf-tutorial`
 place this package inside `~/your_workspace/src` and run 
 `colcon build` inside `~/your_workspace`
 Don't forget to source `install/setup.bash`
 Package name is rover_simulation (change to this if it is different)
 in order to launch the urdf in Rviz, `ros2 launch rover_simulation display.launch.py model:=urdf/robotic_arm_moveit_model_urdf.urdf`