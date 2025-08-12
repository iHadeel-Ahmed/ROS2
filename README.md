# ROS2 Turtlesim Project

This project demonstrates basic **ROS 2** commands and concepts using the `turtlesim` package.  
It covers running Turtlesim, controlling the turtle, listing nodes and topics, and checking topic information.

---

## 1️⃣ Source ROS 2 Environment
Before running any ROS 2 command, source the environment:
```bash
source /opt/ros/humble/setup.bash
# ROS2 Turtlesim Project

This project demonstrates basic **ROS 2** commands and concepts using the `turtlesim` package.
It covers running Turtlesim, controlling the turtle, listing nodes and topics, and checking topic information.

## 1️⃣ Source ROS 2 Environment

Before running any ROS 2 command, source the environment:
\`\`\`bash
source /opt/ros/humble/setup.bash
\`\`\`

## 2️⃣ Run Turtlesim Node

Launch the Turtlesim simulation:
\`\`\`bash
ros2 run turtlesim turtlesim\_node
\`\`\`
📌 This will open a window showing the turtle in the simulation.

## 3️⃣ Control the Turtle with Keyboard

In a new terminal:
\`\`\`bash
ros2 run turtlesim turtle\_teleop\_key
\`\`\`
**Controls:**

* Arrow keys → Move the turtle.
* Keys \`G | B | V | C | D | E | R | T\` → Rotate turtle to specific angles.
* \`Q\` → Quit teleop.

## 4️⃣ List Nodes

\`\`\`bash
ros2 node list
\`\`\`

## 5️⃣ List Topics

\`\`\`bash
ros2 topic list
\`\`\`

## 6️⃣ Get Node Info

\`\`\`bash
ros2 node info /turtlesim
\`\`\`

## 7️⃣ Get Topic Info

\`\`\`bash
ros2 topic info /turtle1/cmd\_vel
\`\`\`

## 📷 Screenshots

Screenshots of the commands and results are stored in the [\`screenshots/\`](screenshots) folder.

* **Running Turtlesim & Listing Nodes/Topics**
  ![Turtlesim Node List](screenshots/nodes_topics.png)

* **Turtle Movement in Turtlesim Window**
  ![Turtle Movement](screenshots/turtle_movement.png)

* **Topic Info Command**
  ![Topic Info](screenshots/topic_info.png)

## 📝 Notes

* Always source the ROS 2 environment in every new terminal before running commands.
* You can experiment with other Turtlesim services and topics for more practice.
