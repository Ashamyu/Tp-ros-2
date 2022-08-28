# TP ROS 2

## Installation

Make a git clone of the git repository
```sh
https://github.com/Ashamyu/Tp-ros-2.git
```
---------------------------------------------------------------------------------------------------------------------------------------------------------
**NOTE :** The command "**roscore**" must be open in one terminal and the other commands in another terminal.
## Part 1


>Use the commands below 
```
roscore
rosrun turtle turtlesim_node

rosrun turtlesim turtle_teleop_key
 (Here use arrow keys on keyboard to move turtle)
 
```

## Part 2
```
source devel/setup.bash
roscore
rosrun move_turtle deplacer.py

 (Now set your points)
```

## Part 3
>In another terminal
```

source devel/setup.bash
roscore
rosrun move_turtle turtle_circle.py 1.0 
 (the "1.0" here is very important in this command)

```

----------------------------------------------------
- >Author : SHAMYU GEORGE ADRIEN       -
- >Class : INFO2                       -
- >Module : ROBO                       -




