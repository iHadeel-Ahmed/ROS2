# ROS2 TurtleSim Project

This project demonstrates working with ROS2 Humble using the turtlesim package.  
It covers running the turtle simulation, listing nodes and topics, viewing node information, and checking topic details.

---

## Project Overview
In ROS2:
- Nodes are individual processes that perform computation.  
- Topics are named buses over which nodes exchange messages.

In this project:
- The turtlesim_node runs the simulation and handles turtle movement.
- Other nodes send or receive information, such as velocity commands or sensor data.
- Topics are used for communication between these nodes.

---

## Nodes in the Project

When listing active nodes, the main ones include:
- /turtlesim: Runs the TurtleSim simulation.
- /teleop_turtle: Allows controlling the turtle using the keyboard.

Example - `/turtlesim` Node:
- Subscribers: Receive data from other nodes.
  - /parameter_events → Parameter changes in ROS2.
  - /turtle1/cmd_vel → Velocity commands for the turtle.
- Publishers: Send data to other nodes.
  - /turtle1/color_sensor → Turtle's position color data.
  - /turtle1/pose → Turtle's current position and orientation.
- Services: Perform specific tasks when requested.
  - /spawn → Create a new turtle.
  - /reset → Reset the simulation.
- Action Servers:
  - /turtle1/rotate_absolute → Rotate turtle to a specific angle.

---

## Topics in the Project

Topics allow nodes to send and receive messages without direct connection.  

Example - `/turtle1/cmd_vel` Topic:
- Type: geometry_msgs/msg/Twist (linear and angular velocity)
- Publisher Count: 2 (nodes sending movement commands)
- Subscription Count: 2 (nodes receiving these commands)

---

## Screenshots

- screenshot of the executed commands and their output
- screenshot of the executed commands and their output 2
- screenshot of the executed commands and their output 3

---

## Requirements
- Ubuntu (running in VirtualBox or directly)
- ROS2 Humble installed
- turtlesim package installed
