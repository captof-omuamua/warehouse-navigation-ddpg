# Extracted robot base source

The 117 files in robot-base-source/bcr_bot-ros2/ were extracted without modification from robot-base-source.zip on this branch. The original ZIP is retained.

This is the ROS 2 bcr_bot robot model and Gazebo warehouse simulation package, not the DDPG training implementation. All original source and licensing files are preserved.

The separately imported reinforcement-main.zip is ROS Noetic/catkin configuration, checkpoints and documentation, with its src/reinforcement training package missing. A SHA-256 comparison found no byte-identical files between the 117 robot archive files and the 46 retained reinforcement project files (excluding generated web dependencies/cache/dist). Shared robotics terminology does not establish shared implementation. Runtime integration was not tested.
