# trash_nav

### List of Commands for Launching 
Run these commands from trash_parent_repo and then source from catkin_ws
```
roslaunch turtlebot_bringup minimal.launch
roslaunch realsense2_camera rs_rgbd.launch
roslaunch turtlebot_navigation amcl_demo.launch map_file:=/home/trash/<path to map.yaml>
roslaunch depthimage_to_laserscan launchfile_trash.launch
```

### List of Commands to View
```
roslaunch turtlebot_rviz_launchers view_navigation.launch --screen
```

