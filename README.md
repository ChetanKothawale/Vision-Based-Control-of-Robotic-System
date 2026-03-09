Vision-Based Control of Robotic SystemM.Tech Thesis Project | Chetan Kothawale📌 Project OverviewThis repository contains the source code, documentation, and evaluation reports for an M.Tech Thesis project focused on the Vision-Based Control (VBC) of a robotic system. The core objective is to implement a closed-loop control system where visual data from a camera (eye-in-hand or eye-to-hand configuration) is used to guide the robot's end-effector to a target position or to track a dynamic object.🎯 Key ObjectivesVisual Servoing: Implementing Image-Based Visual Servoing (IBVS) or Position-Based Visual Servoing (PBVS).Object Tracking: Real-time detection and tracking of targets using computer vision algorithms.Control Loop Integration: Minimizing the error between current visual features and desired target features.Precision & Stability: Ensuring the robotic arm reaches the target with minimal steady-state error and oscillation.🛠️ Methodology & ArchitectureThe system follows a standard vision-control pipeline:Image Acquisition: Capturing live frames via a camera (e.g., Logitech Webcam, Kinect, or RealSense).Feature Extraction: Identifying key points, color markers, or geometric shapes using OpenCV.Control Law: Calculating the required joint velocities/torques based on the visual error.Robot Actuation: Sending commands to the robot via ROS (Robot Operating System) or a serial interface (Arduino/Microcontroller).📂 Repository Structure.
├── Midterm_evaluation      # Progress reports, presentations, and evaluation results
├── src                     # Source code for vision and control nodes
│   ├── perception          # Object detection and tracking scripts
│   └── controller          # PID / Visual Servoing implementation
├── docs                    # Thesis documentation and research papers
└── README.md               # Project documentation
🚀 Getting StartedPrerequisitesPython 3.xOpenCV (pip install opencv-python)NumPy (pip install numpy)ROS (Noetic/Melodic) (Optional, based on implementation)InstallationClone the repository:git clone [https://github.com/ChetanKothawale/Vision-Based-Control-of-Robotic-System.git](https://github.com/ChetanKothawale/Vision-Based-Control-of-Robotic-System.git)
Install dependencies:pip install -r requirements.txt
Running the System(Update these commands based on your specific script names)# To start the vision-based tracking node
python src/perception/track_object.py

# To launch the robot control loop
python src/controller/main_control.py
📊 EvaluationThe Midterm_evaluation folder contains detailed analysis of:Error convergence graphs.System response time.Accuracy of the vision algorithms under varying lighting conditions.🤝 AcknowledgmentsSpecial thanks to my thesis supervisor and the department for providing the necessary robotic hardware and lab facilities.📄 LicenseThis project is licensed under the MIT License - see the LICENSE file for details.Contact: Chetan Kothawale
