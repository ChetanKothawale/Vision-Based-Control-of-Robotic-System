Vision-Based Control of Robotic System

M.Tech Thesis Project | Chetan Kothawale

📌 Project Overview

This repository contains the source code, documentation, and evaluation reports for an M.Tech Thesis project focused on the Vision-Based Control (VBC) of a robotic system. The core objective is to implement a closed-loop control system where visual data from a camera (eye-in-hand or eye-to-hand configuration) is used to guide the robot's end-effector to a target position or to track a dynamic object.

🎯 Key Objectives

1. Visual Servoing: Implementing Image-Based Visual Servoing (IBVS) or Position-Based Visual Servoing (PBVS).

2. Object Tracking: Real-time detection and tracking of targets using computer vision algorithms.

3. Control Loop Integration: Minimizing the error between current visual features and desired target features.

4. Precision & Stability: Ensuring the robotic arm reaches the target with minimal steady-state error and oscillation.

🛠️ Methodology & Architecture

The system follows a standard vision-control pipeline:

1. Image Acquisition: Capturing live frames via a camera (e.g., Logitech Webcam, Kinect, or RealSense).

2. Feature Extraction: Identifying key points, color markers, or geometric shapes using OpenCV.

3. Control Law: Calculating the required joint velocities/torques based on the visual error.

4. Robot Actuation: Sending commands to the robot via ROS (Robot Operating System) or a serial interface (Arduino/Microcontroller).



📊 Evaluation

The Midterm_evaluation folder contains detailed analysis of:

Error convergence graphs.

System response time.

Accuracy of the vision algorithms under varying lighting conditions.

🤝 Acknowledgments

Special thanks to my thesis supervisor and the department for providing the necessary robotic hardware and lab facilities.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact: Chetan Kothawale
