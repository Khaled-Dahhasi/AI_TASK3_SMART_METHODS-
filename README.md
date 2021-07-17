# AI_TASK3_SMART_METHODS-

This work is for my third task in the AI route at [Smart Methods'](https://s-m.com.sa/c12_in.php) training program.

## Task Description 
Using another ROS robot with SLAM approach to create and save a map.
The ROS robot used will be [Devansh Dhrafani's diff_drive_bot.](https://github.com/devanshdhrafani/diff_drive_bot)

SLAM and other packages are already intalled from [the previous Task](https://github.com/Khaled-Dahhasi/AI_TASK2_SMART_METHODS-/blob/main/README.md)

## Task Steps
1- Install the bot using the installation instructions from the [developer's page](https://github.com/devanshdhrafani/diff_drive_bot)

2- We will launch and load the bot in the turtlebot3 house environment in gazepo and control it via keyboard.
![bot In Gazebo House](https://user-images.githubusercontent.com/85564881/126045254-34f0a14f-3c3e-4adb-9fb6-1a985189912c.png)


3- move it around untill we get a satisfactory map using SLAM.
![](https://user-images.githubusercontent.com/85564881/126045588-9204500f-c745-4ed3-b3a8-00049ba7ae7e.gif)


4- Save the map using the command: `rosrun map_server map_saver -f ~/map`
![Saved Map](https://user-images.githubusercontent.com/85564881/126045291-daff3e9e-3c13-4a94-aff7-8ac28015ddeb.png)
