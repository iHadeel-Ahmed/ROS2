

# ROS2 Turtlesim Project

This project demonstrates basic **ROS 2** commands and concepts using the `turtlesim` package.  
It covers running Turtlesim, controlling the turtle, listing nodes and topics, and checking topic information.

## 1. Source ROS 2 Environment
Before running any ROS 2 command, source the environment:
```bash
source /opt/ros/humble/setup.bash
````

## 2. Run Turtlesim Node

Launch the Turtlesim simulation:

```bash
ros2 run turtlesim turtlesim_node
```

This will open a window showing the turtle in the simulation.

## 3. Control the Turtle with Keyboard

In a new terminal:

```bash
ros2 run turtlesim turtle_teleop_key
```

Controls:

* Arrow keys → Move the turtle.
* Keys `G | B | V | C | D | E | R | T` → Rotate turtle to specific angles.
* `Q` → Quit teleop.

## 4. List Nodes

```bash
ros2 node list
```

## 5. List Topics

```bash
ros2 topic list
```

## 6. Get Node Info

```bash
ros2 node info /turtlesim
```

## 7. Get Topic Info

```bash
ros2 topic info /turtle1/cmd_vel
```

## Screenshots

- screenshot of the executed commands and their output
- screenshot of the executed commands and their output2
- screenshot of the executed commands and their output3



## Notes

* Always source the ROS 2 environment in every new terminal before running commands.
* You can experiment with other Turtlesim services and topics for more practice.


