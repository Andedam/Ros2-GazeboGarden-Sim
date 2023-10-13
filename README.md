# Ros2-GazeboGarden-Sim
Tutorial and .sdf files for the simulation environment of an airport. Including scripts for a dynamic environment

**OS:**
Ubuntu 20.04

**Install Ros1 Noetic:**
...

**Install Gazebo 11:**
...

**Copy/Paste/Move files from /usr/:**
sudo -H nautilus

**Run the simulation:**
- Modify vecadis_sim_dev and vecadis_sim to include/exclude aircraft and change .world
- Change arg:=deicer_position in vecadis_sim_dev.launch from "behind_right_angled" to "TestCases" (.yaml)
- rosrun vecadis_sim_bringup gzlauncher roslaunch vecadis_sim_bringup vecadis_sim_dev.launch






