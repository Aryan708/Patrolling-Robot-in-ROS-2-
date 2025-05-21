# 🤖 Patrolling Robot in ROS 2 + Gazebo

A ROS 2-based simulation project that enables a robot to patrol through a series of predefined waypoints in a 2D environment. The robot uses the Navigation2 stack (`nav2_simple_commander`) to autonomously move, avoid dynamic obstacles, return to the starting position, and log patrol history.

---

## 📌 Features

- Autonomous waypoint navigation using ROS 2
- Dynamic obstacle avoidance using Navigation2
- Return-to-start behavior
- Timestamped logging of visited waypoints
- Modular Python-based ROS 2 node
- Simulated in Gazebo (optional), or can be tested in headless mode

---

## 🧱 Requirements

- Ubuntu 22.04 or 20.04
- [ROS 2 Humble](https://docs.ros.org/en/humble/Installation.html) (or Foxy)
- `nav2_simple_commander` (`ros-humble-nav2-simple-commander`)
- Python 3.8+
- Optional: Gazebo and RViz2 for visualization

---

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/<your-username>/patrolling-robot.git
cd patrolling-robot
