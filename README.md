# Autonomous EKF-SLAM Navigation System

## Overview

The **Autonomous EKF-SLAM Navigation System** is a robotics and autonomous navigation project that implements **Simultaneous Localization and Mapping (SLAM)** using the **Extended Kalman Filter (EKF)**. The system is designed for a differential drive mobile robot operating in an unknown indoor environment.

The project enables the robot to estimate its own position while simultaneously building a map of environmental landmarks using **probabilistic sensor fusion** and **state estimation** techniques.

The implementation combines robot kinematics, motion control, EKF prediction and update steps, landmark mapping, obstacle avoidance, and real-time visualization into a complete autonomous navigation framework.

---

## Features

- Extended Kalman Filter (EKF) based SLAM
- Differential drive robot navigation
- Real-time localization and mapping
- Probabilistic sensor fusion
- Landmark-based environment mapping
- Autonomous waypoint navigation
- Obstacle avoidance system
- Real-time trajectory visualization
- Odometry and EKF comparison
- Gaussian noise modeling
- Real-time estimation error tracking

---

## Technologies Used

### Programming Language
- Python

### Libraries and Modules
- NumPy
- Matplotlib
- Pygame
- Math

---

## Core Concepts Implemented

- Simultaneous Localization and Mapping (SLAM)
- Extended Kalman Filter (EKF)
- Differential Drive Robot Kinematics
- Sensor Fusion
- Motion Prediction
- State Estimation
- Probabilistic Robotics
- Landmark Detection and Mapping
- Obstacle Avoidance
- Autonomous Navigation

---

## System Workflow

1. Robot receives motion control inputs
2. EKF prediction step estimates robot pose
3. Sensor observations detect landmarks
4. EKF update step corrects state estimates
5. Landmark positions are updated
6. Real-time map and trajectory are visualized
7. Robot navigates autonomously through waypoints

---

## Project Structure

    project/
    │
    ├── main.py
    ├── ekf_slam.py
    ├── robot.py
    ├── sensors.py
    ├── visualization.py
    ├── utils.py
    ├── requirements.txt
    └── README.md

---

## Installation

### Clone the Repository

    git clone <your-github-repository-link>
    cd Autonomous-EKF-SLAM-Navigation-System

### Install Dependencies

Make sure **Python 3** is installed, then install all required libraries:

    pip install -r requirements.txt

Or install manually:

    pip install numpy matplotlib pygame

---

## Run the Project

    python main.py

If your system uses Python 3 explicitly:

    python3 main.py

---

## Simulation Output

The simulation displays:

- Ground truth robot trajectory
- EKF estimated trajectory
- Odometry-only trajectory
- Landmark positions
- Real-time localization error
- Sensor observations
- Obstacle avoidance behavior

---

## Performance Results

The EKF-SLAM system significantly reduces localization error compared to odometry-only navigation.

| Method         | Mean Error |
|----------------|------------|
| Odometry Only  | 0.85 m     |
| EKF-SLAM       | 0.18 m     |

The system demonstrates improved localization accuracy and consistent landmark estimation.

---

## Advantages

- Improved localization accuracy
- Reduced cumulative odometry drift
- Real-time autonomous navigation
- Probabilistic uncertainty handling
- Scalable robotics architecture
- Efficient sensor fusion framework

---

## Future Improvements

- Real-world robot deployment
- LiDAR and camera integration
- Graph-based SLAM implementation
- ROS integration
- Multi-robot SLAM
- Advanced obstacle avoidance
- Deep Learning based perception

---

## Learning Outcomes

Through this project, the following skills were developed:

- EKF-SLAM Algorithm Development
- Robotics Localization and Mapping
- Sensor Fusion and Probabilistic Estimation
- Differential Drive Robot Kinematics
- Autonomous Navigation System Design
- Kalman Filtering Techniques
- Real-Time Robotics Simulation
- Mathematical Modeling for Robotics

---

## Authors

- Aneesh Adithya SR
- Abhay Aditya N
- Arun Koushik B A
- Navith

---

## License

This project is developed for academic and educational purposes.
