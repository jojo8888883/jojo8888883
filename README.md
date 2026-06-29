# Hi, I'm Yuzhou Chen 👋

Incoming MSc student in **Smart Manufacturing at HKUST(GZ)**, working on **robot learning**, **dexterous manipulation**, **vision-based teleoperation**, and **generated-video-to-trajectory pipelines**.

I am interested in building robot learning systems that connect:

* generated / ordinary videos
* hand-object trajectory parsing
* dexterous hand teleoperation
* RGB-D data pipelines
* simulation environments
* real-robot manipulation systems

Currently, I am focusing on the intermediate layer between **video understanding** and **robot execution**: how to convert visual human-object interaction data into structured hand-object trajectories, datasets, diagnostics, and robot learning pipelines.

---

## Featured Projects

### 🦾 B.Eng. Thesis: Generated-Video-to-Trajectory Pipeline for Dexterous Manipulation

[GitHub](https://github.com/jojo8888883/beng-thesis-hand-object-trajectory)

Built a generated-video-to-trajectory pipeline for dexterous manipulation, integrating **Depth Any Video**, **HaMeR**, **FoundationPose**, and a **PIOM-based trajectory optimization module** to parse human-object interaction videos into structured hand-object trajectories.

**Highlights**

* Designed a standardized hand-object trajectory format including wrist pose, MANO hand state, object 6-DoF pose, hand/object point clouds, valid-frame masks, and metadata.
* Adapted a physics-consistent trajectory optimization module for hand-object trajectory refinement.
* Ran multi-GPU PyTorch DDP experiments on an 8×NVIDIA A800-SXM4-80GB server.
* Evaluated on DexYCB using MPJPE, ADD-S, FD(hand), FD(object), hand-object minimum distance, and jerk metrics.
* Validated batch inference on 252 generated-video samples, with 245 reaching PIOM inference and 207/245 successful cases showing improved hand-object minimum distance.

---

### 🎥 DexC2D: Generated-Video-to-Dataset Pipeline

[GitHub](https://github.com/jojo8888883/DexC2D)

Developed an automated data pipeline for dexterous manipulation, converting generated human-object interaction videos and RealSense RGB-D captures into structured datasets for downstream imitation learning and trajectory parsing.

**What it does**

* Captures RGB-D data with RealSense cameras.
* Converts generated videos into frame sequences.
* Organizes RGB, depth, CAD metadata, and camera intrinsics.
* Handles resolution mismatch between RealSense captures and generated videos.
* Produces object-level dataset folders compatible with downstream robot learning pipelines.

---

### 🤖 ReKep-Kinova: Real-World Reproduction Setup

[GitHub](https://github.com/jojo8888883/ReKep-Kinova)

Worked on adapting **ReKep** toward a Kinova arm + RealSense D435i setup, including simulation deployment, perception-hardware interface preparation, and debugging for real-world manipulation reproduction.

**Scope**

* Deployed ReKep with OmniGibson and Isaac Sim.
* Debugged Conda, Open3D, PyTorch, Isaac Sim, dataset, and runtime compatibility issues.
* Prepared Kinova + RealSense real-world reproduction environment.
* Documented limitations of sim-only reproduction and real-world setup requirements.

---

## Selected Robotics Experience

### Shenzhen Institute of Artificial Intelligence and Robotics for Society

**Robotics Intern | Jan. 2025 – Jul. 2025**

Worked on dexterous manipulation and robot learning systems involving real robots, dexterous hands, RGB-D cameras, teleoperation, and simulation.

**Main work**

* Reproduced and adapted **DexGraspVLA** on a UR5 + Inspire Hand platform.
* Integrated model inference, dexterous hand control, robot arm control, and RealSense image capture.
* Built trajectory diagnostic tools for visualizing state/action curves, predicted TCP trajectories, real TCP trajectories, timestamp alignment, and point-wise error.
* Supported data collection and training diagnostics for DexGraspVLA, including multi-object demonstrations, background augmentation, BF16 training checks, and early failure-mode analysis.
* Explored single-camera **Allegro Hand vision-based teleoperation** in both real-world and Sapien simulation environments.
* Set up AnyTeleop and dex-hand-teleop baselines, studying human-hand pose retargeting and the sim-to-real action interface.
* Maintained and extended dexterous grasping code related to **Grasp What You Want**, including side-grasp planning, waypoint generation, and execution logic.

### Machine Intelligence and Advanced Adaptation Lab, SCUT

**Robotics Intern | Sep. 2024 – Dec. 2024**

* Deployed and debugged ReKep with Isaac Sim / OmniGibson on Windows and Ubuntu machines.
* Investigated simulation failures caused by dependency conflicts, asset paths, cached API queries, random seeds, and simulator instability.
* Contributed to adapting ReKep toward a Kinova arm + RealSense D435i real-world setup.

---

## Technical Interests

* Dexterous manipulation
* Robot learning
* Vision-based teleoperation
* Video-to-trajectory parsing
* Hand-object trajectory representation
* RGB-D data pipelines
* Imitation learning and VLA-related pipelines
* Sim-to-real robotic manipulation

---

## Skills

**Robotics & Manipulation**
ROS / ROS2, dexterous manipulation, vision-based teleoperation, hand-object trajectory parsing, robot grasping, sim-to-real workflow

**Simulation & Robot Platforms**
Sapien, Isaac Sim, OmniGibson, UR5, Kinova, Allegro Hand, Inspire Hand, RealSense D435 / D405

**Machine Learning & Perception**
PyTorch, PyTorch DDP, imitation learning, VLA-related pipelines, YOLOv5, TFLite, Edge Impulse, video-based data generation

**Programming & Tools**
Python, C++, Linux / Ubuntu, Git, Docker, Conda, Bash, LaTeX

---

## Contact

📧 Email: [chanjoe929@gmail.com](mailto:chanjoe929@gmail.com)
🔗 GitHub: [jojo8888883](https://github.com/jojo8888883)
