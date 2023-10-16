Garden# Ros1-Gazebo11-Sim
Tutorial and .sdf files for the simulation environment of an airport. Including scripts for a dynamic environment

**OS:**
Ubuntu 20.04

**Install Ros1 Noetic:**
...

**Install Gazebo 11:**
...

**Copy/Paste/Move files from /usr/:**
sudo -H nautilus

**Catvehicle:**
- roslaunch catvehicle catvehicle_spawn.launch

**Run the simulation (other test cases):**
- Modify vecadis_sim_dev and vecadis_sim to include/exclude aircraft and change .world
- Change arg:=deicer_position in vecadis_sim_dev.launch from "behind_right_angled" to "TestCases" (.yaml)
- rosrun vecadis_sim_bringup gzlauncher roslaunch vecadis_sim_bringup vecadis_sim_dev.launch



**Run Case 15:**
- cd ~/repos/vecadis_nac/catkin_ws
  - roslaunch vecadis_sim_bringup Case15.launch
- cd ~/repos/vecadis_nac/catkin_ws/src/catvehicle/src
  - ./TestAhead.py
 
**Run Case 8:**
- cd ~/repos/vecadis_nac/catkin_ws/src/catvehicle/src
  - roslaunch vecadis_sim_bringup Case8.launch
- cd ~/repos/vecadis_nac/catkin_ws/src/catvehicle/src
  - ./TestAhead.py






