# mars_lite_simulation_ws
Experimental ROS workspace for the simulation of the MARS mobile manipulator.

<img src="figures/mars_lite_gazebo_simple_demo.gif" width=100% alt="mars_lite_gazebo_simple_demo" />

### Dependencies
```bash
# Make sure you have installed ROS1 and Moveit first !!
sudo apt-get update
sudo apt-get install -y ros-${ROS_DISTRO}-joint-trajectory-controller \
    ros-${ROS_DISTRO}-gripper-action-controller
```