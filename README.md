# Self-Driving Cars: Level 2 with Carla Simulator (Python)
This project explores the development of a Level 2 autonomous vehicle model using Python within the Carla simulator. It provides an in-depth learning experience in vehicle dynamics modeling, control systems, and the core functionalities of self-driving cars.

## Project Overview
This repository implements a Level 2 autonomous vehicle model in the Carla simulator, a popular open-source platform for developing and testing self-driving algorithms.  The core functionalities include:

### Vehicle Dynamics Modeling
A simplified bicycle model is used to represent the car's kinematic and dynamic behavior. This model captures the essential relationships between steering, acceleration, and the car's motion.

### Control Systems
Two key controllers are implemented:
#### 1. PID Controller (Longitudinal Control)
This controller manages the vehicle's speed by adjusting throttle and brake based on the desired speed.
#### 2. Stanley Controller (Lateral Control)
This controller calculates the appropriate steering angle to follow a predefined trajectory.

### Carla Integration
The Python code interacts with the Carla simulator to control the virtual vehicle and receive sensor data (e.g., camera images, LiDAR scans).

## Project Highlights
### Level 2 Autonomy
This model focuses on Level 2 autonomy, where the car can handle some aspects of driving (longitudinal and lateral control) but requires human supervision for complex situations and safety.

### Implementation in Python
Python is used for its readability, extensive libraries (suitable for scientific computing and control systems), and popularity in the autonomous vehicle development community.

### Carla Simulator
Carla provides a realistic and flexible environment to test and refine the autonomous driving model without the risks and complexities of real-world testing.

## Results and Learnings
The implemented model achieved a success rate of 79.18% in following the waypoints of a predefined trajectory within the Carla simulator. This demonstrates a functional understanding of the core components involved in self-driving cars.

The project offers valuable learnings in:
1. Autonomous Vehicle Principles: Understanding the fundamental concepts behind Level 2 autonomy, including vehicle dynamics modeling and control systems.
2. Python Programming: Applying Python for scientific computing, control algorithms, and interfacing with the Carla simulator.
3. Carla Simulator Usage: Gaining hands-on experience with the Carla platform for simulating and testing autonomous driving models.
