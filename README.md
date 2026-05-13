# Hi, I'm Yuzhou Chen 👋

Incoming MSc student in Smart Manufacturing at HKUST(GZ), focusing on **dexterous manipulation**, **vision-based teleoperation**, and **generated-video-to-trajectory pipelines** for robot learning.

I work on systems that connect:

- generated / ordinary videos
- hand-object trajectory parsing
- dexterous hand teleoperation
- RGB-D data pipelines
- simulation-to-real robot manipulation

## Featured Projects

### 🦾 B.Eng. Thesis: Generated-Video-to-Trajectory Pipeline for Dexterous Manipulation
[GitHub](https://github.com/jojo8888883/beng-thesis-hand-object-trajectory)

Built a generated-video-to-trajectory pipeline for dexterous manipulation, integrating Depth Any Video, HaMeR, FoundationPose, and PIOM to parse human-object interaction videos into structured hand-object trajectories.

Highlights:
- Designed a standardized hand-object trajectory format with hand pose, MANO state, object 6-DoF pose, point clouds, valid-frame masks, and metadata.
- Ran multi-GPU PyTorch DDP experiments on an 8×A800 server.
- Evaluated on DexYCB with MPJPE, ADD-S, FD(hand), FD(object), minimum-distance, and jerk metrics.
- Validated batch inference on 252 generated-video samples, with 245 reaching PIOM inference.

### 🎥 DexC2D: Generated-Video-to-Dataset Pipeline
[GitHub](https://github.com/jojo8888883/DexC2D)

Developed an automated data pipeline for dexterous manipulation, converting generated human-object interaction videos and RealSense RGB-D captures into structured RGB/depth/CAD/camera-metadata datasets for downstream imitation learning.

### 🤖 ReKep-Kinova: Real-World Reproduction Setup
[GitHub](https://github.com/jojo8888883/ReKep-Kinova)

Worked on adapting ReKep toward a Kinova arm + RealSense D435i setup, including perception-hardware interface preparation, Isaac Sim / Ubuntu environment setup, and debugging for real-world manipulation reproduction.

## Experience Snapshot

### Shenzhen Institute of Artificial Intelligence and Robotics for Society (AIRS)
**Robotics Intern | Jan. 2025 – Jul. 2025**

Worked on dexterous manipulation systems involving:

- DexGraspVLA reproduction on UR5 + Inspire Hand
- generated-video data pipelines for dexterous manipulation
- Allegro Hand vision-based teleoperation
- Sapien simulation and dexterous hand retargeting
- ROS-based hand control and RealSense RGB-D data processing

### Machine Intelligence and Advanced Adaptation Lab (MIAA), SCUT
**Robotics Intern | Sep. 2024 – Dec. 2024**

Worked on ReKep reproduction and deployment with Isaac Sim / OmniGibson, Kinova arm, and RealSense D435i, focusing on simulation setup, dependency debugging, and real-world reproduction preparation.

## Technical Interests

- Dexterous manipulation
- Vision-based teleoperation
- Video-to-trajectory parsing
- Robot learning data pipelines
- Sim-to-real robotic manipulation
- RGB-D perception for robot grasping

## Skills

**Robotics & Manipulation:** ROS, dexterous manipulation, vision-based teleoperation, robot grasping, hand-object trajectory parsing  
**Simulation & Robot Platforms:** Sapien, Isaac Sim, OmniGibson, UR5, Kinova, Allegro Hand, Inspire Hand, RealSense D435/D405  
**ML & Perception:** PyTorch, PyTorch DDP, imitation learning, VLA-related pipelines, YOLOv5, TFLite, Edge Impulse  
**Programming & Tools:** Python, C++, Linux/Ubuntu, Git, Docker, Conda, Bash, LaTeX  

## Contact

📧 Email: chanjoe929@gmail.com  
🔗 GitHub: [jojo8888883](https://github.com/jojo8888883)
