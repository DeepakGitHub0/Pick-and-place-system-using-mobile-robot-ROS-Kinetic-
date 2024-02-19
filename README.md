This project implements a robotic pick and place system using a TurtleBot manipulator and Robot Operating System (ROS) Kinetic.
The system executes preset motion sequences in Python to grasp, transport, and release objects without sensor feedback. 
To improve grasping reliability compared to the rigid default gripper, a soft robotic gripper was designed and fabricated with string actuation. Using the MoveIt motion planning libraries in ROS, the gripper controls and arm motions were programmed to achieve pick and place poses.

This code implements the pick and place sequences on a TurtleBot using MoveIt and the custom soft gripper.
The Python node controls the arm to move to predefined pick and place joint poses. It also commands the gripper to open and close at the appropriate times.

 Key aspects include:

Motion planning with MoveIt
Controlling soft gripper actuation
Achieving pick and place poses without sensor feedback
Grasping, transport and release of objects

Overall this demonstrates programming a mobile manipulator to complete pick and place tasks. 
The custom gripper and preset poses provide a simple parts handling system using ROS and affordable open-source robotics platforms.
