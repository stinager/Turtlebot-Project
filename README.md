# Turtlebot-Project
## Robotics & Smart Home Communication Project (group of 4 students)

The goal of this project is to make the robot communicate with the environment in which it operates, based on two communication technologies: **IEEE 802.11 (Wi-Fi)** and **IEEE 802.15.4 (ZigBee)**.

Each robot is equipped with a netbook connected via Wi-Fi, and also a **ZigBee chip** interfaced through the robot's netbook via a **USB-connected Arduino controller**.

In addition to the robot, several **Arduino Mega controllers** equipped with ZigBee chips, sensors, and/or actuators will be distributed within the environment to simulate various communicating objects (e.g., light bulbs, door locks, smoke detectors).

Finally, a **web interface** will allow tracking the robot's movement on a map and visualizing its different states (programmed mode, event-driven mode).

To create an environment for the robot, we performed a mapping of the room by running SLAM with **Gmapping**, resulting in two useful files for further steps:

- mapi5new.pgm
- mapi5new.yaml

  
The **exemple_move_base.py** file allows the robot to reach **three checkpoint**s consecutively on the associated map.
Additional information has been added to monitor the robot's battery level and the netbook's battery level.
