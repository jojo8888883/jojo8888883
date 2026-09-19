# Hi, I'm Yuzhou Chen 👋

I'm an MSc student in **Smart Manufacturing at HKUST(GZ)**, with a B.Eng. in **Robotics Engineering from South China University of Technology**.

My research interests are **robot learning from human demonstrations**, **egocentric video understanding**, and **dexterous manipulation**. I am particularly interested in how visual observations of human–object interactions can provide useful representations and supervision for robot learning.

My experience spans hand–object trajectory modeling, multimodal data processing, model training and evaluation, and real-robot integration. Previously, I worked on dexterous manipulation and VLA systems at AIRS, and simulation and robot integration at SCUT's MIAA Lab.

## Selected Projects

### QuietHand · Egocentric Hand–Object Interaction Annotation

A research prototype for structuring bimanual interactions from egocentric RGB-D videos.

- Built a pipeline combining VLM action descriptions, hand reconstruction, object segmentation, and 6-DoF object pose estimation.
- Aligned semantic and geometric evidence across time and object identities, with explicit records of missing or uncertain predictions.
- Developed visual review and diagnostic tools, and explored geometric evidence for prioritizing annotation review.

### [B.Eng. Thesis · Hand–Object Trajectory Parsing and Refinement](https://github.com/jojo8888883/beng-thesis-hand-object-trajectory)

A pipeline for extracting and refining structured hand–object trajectories from interaction videos.

- Integrated visual parsing with wrist pose, MANO hand state, object pose, and point-cloud representations.
- Adapted a PIOM-based trajectory refinement module and ran multi-GPU PyTorch DDP training and evaluation on DexYCB.
- Analyzed pose errors, temporal consistency, and hand–object geometry, with additional batch inference on generated videos.

### [DexC2D · RGB-D and Generated-Video Data Processing](https://github.com/jojo8888883/DexC2D)

Tools for RealSense RGB-D capture, video frame extraction, resolution alignment, and camera/CAD metadata organization, preparing inputs for trajectory parsing and robot-learning experiments.

## Robotics Experience

**AIRS · Robotics Intern · Jan–Jul 2025**

- Contributed to DexGraspVLA reproduction on a UR5 + Inspire Hand platform, integrating model inference, arm/hand control, and RealSense capture for grasping experiments.
- Built tools to align and compare predicted and executed TCP trajectories, and supported demonstration collection and training diagnostics.
- Worked on Allegro Hand visual teleoperation with AnyTeleop and dex-hand-teleop, and extended grasp-planning and execution code.

**SCUT MIAA Lab · Robotics Intern · Sep–Dec 2024**

- Deployed and debugged ReKep with OmniGibson and Isaac Sim.
- Contributed to perception-interface and environment preparation for a [Kinova + RealSense adaptation](https://github.com/jojo8888883/ReKep-Kinova).

## Tools & Platforms

**Learning & programming:** PyTorch, distributed training, Python, C++, Linux, Git, Docker.

**Robotics & simulation:** ROS/ROS2, Isaac Sim, OmniGibson, Sapien, UR5, Kinova, Allegro Hand, Inspire Hand, RealSense.

## Contact

I'm interested in research collaborations on learning from human videos, hand–object interaction, and robot manipulation.

[Email](mailto:chanjoe929@gmail.com) · [GitHub](https://github.com/jojo8888883)
