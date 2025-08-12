

⸻

ROS2 TurtleSim Project

This project demonstrates working with ROS2 Humble using the turtlesim package.
The steps include running the turtle simulation, listing nodes, topics, and node info, as well as checking topic information.

Requirements
 • Ubuntu (running in VirtualBox or directly)
 • ROS2 Humble installed
 • turtlesim package installed

Steps Performed
 1. Source ROS2 environment:

source /opt/ros/humble/setup.bash


 2. Launch TurtleSim:

ros2 run turtlesim turtlesim_node


 3. List active nodes:

ros2 node list


 4. List available topics:

ros2 topic list


 5. Check node info:

ros2 node info /turtlesim


 6. Check topic info:

ros2 topic info /turtle1/cmd_vel



How to Run
 1. Clone the repository:

git clone https://github.com/USERNAME/REPO-NAME.git


 2. Navigate to the project folder:

cd REPO-NAME


 3. Make sure ROS2 Humble is installed and sourced:

source /opt/ros/humble/setup.bash


 4. Run the TurtleSim node:

ros2 run turtlesim turtlesim_node


 5. Open another terminal (with ROS2 sourced) to control or inspect the simulation.

Screenshots
 • Simulation running with turtle drawing shapes.

 • Node and topic listing in the terminal.

 • Topic info output.


⸻


