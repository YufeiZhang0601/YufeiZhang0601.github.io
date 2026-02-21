---
layout: archive
title: "简历 | CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

**Downloads**
* [Yufei Zhang — CV (PDF)](/files/Yufei%20Zhang_CV.pdf)
* [Academic Transcript (PDF)](/files/transcript/transcript.pdf)
* **Publication PDFs**
  * [Attention U-net for Cell Instance Segmentation](/files/publication/Attention%20U-net%20for%20Cell%20Instance%20Segmentation.pdf)
  * [Attention-based Mask R-CNN for Microvascular Segmentation](/files/publication/Attention_based_Mask_R_CNN_for_Microvascular_Segmentation%20%283%29.pdf)
  * [Fine-grained Classification and Recognition in Sports Videos](/files/publication/Fine_grained_Classification_and_Recognition_in_Sports_Videos.pdf)
  * [From Structural Design to Dynamics Modeling — 3-RRR Parallel Ankle](/files/publication/From%20Structural%20Design%20to%20Dynamics%20Modeling%20Control-Oriented%20Development%20of%20a%203-RRR%20Parallel%20Ankle.pdf)
  * [Human-like Lip-Sync Robot Design](/files/publication/Human-like%20Lip-Sync%20Robot%20Design.pdf)
  * [Robust Fault Diagnosis for Gas Turbine Rotor via Transfer RL](/files/publication/Robust%20Fault%20Diagnosis%20for%20Gas%20Turbine%20Rotor%20via%20Transfer%20Reinforcement%20Learning.pdf)

---

## Education

**Columbia University in the City of New York** — 08/2024–Present  
*Master of Science in Engineering* (GPA: 3.75/4.00)  
Coursework: Advanced Spoken Language Processing, Robot Learning, Robotics Studio, Applied Robotics: Algorithms & Software, Data Science for Mechanical Systems, Intro to Control Theory, Mechatronics & Embedded Micro

**University of California, San Diego** — 09/2023–01/2024  
*Exchange Programme*  
Coursework: Natural Language Processing, Mathematics for Robotics, Eng Hands-on Group Project

**Beijing University of Technology (Project 211)** — 08/2020–07/2024  
*Bachelor of Engineering in Robot Engineering* (Major GPA: 3.85/4.00; Overall GPA: 3.69/4.00)  
Overall Average Score: 89.09%

---

## Professional Experience

**Institute of Automation, Chinese Academy of Sciences, Beijing** — 06/2022–09/2023  
*Embedded Engineer Intern*
* Participated in a reinforcement-learning–based dexterous manipulation project using a multi-finger, pure-motor-driven robotic hand.
* Implemented the real-time execution layer by porting the control framework to FreeRTOS, enabling deterministic low-latency control loops required for RL deployment.
* Rewrote joint-level motor drivers, encoder feedback modules, and initialization routines to support stable execution of RL-generated action commands.
* Assisted in integrating the RL policy pipeline (PPO/SAC-based) with the hardware controller through a ROS/TCP interface, supporting real-time action streaming and state feedback.
* Contributed to real-robot tests of manipulation policies, verifying trajectory tracking performance and system stability during RL fine-tuning.

**Microsoft (China) Co., Ltd.** — 01/2022–02/2022  
*MSRA Researcher*
* Selected into the Microsoft Innovative Personnel Cultivation Program; participated in a project on multilingual dialogue generation.
* Processed large-scale conversational datasets and performed linguistic feature analysis, text normalization, and visualization using Python.
* Fine-tuned Transformer-based encoder–decoder models (mBART, mT5) for context-aware responses across multiple languages.
* Conducted experiments on sequence-to-sequence training with attention mechanisms, evaluating semantic coherence, relevance, and cross-language generalization.
* Integrated generated text with Azure Neural TTS (FastSpeech2 + HiFiGAN) for natural speech in conversational AI.
* Participated in the design of the digital avatar pipeline, integrating speech synthesis with facial animation for mouth shapes and head motion in multilingual scenarios.

---

## Academic Projects & Research

**Columbia University: 5-DOF Hippotherapy Rehabilitation System** — 09/2025–Present  
*Research Assistant (Advisor: Prof. Sunil K. Agrawal)*  
* Developed the dynamic model of a 5-DOF hippotherapy rehabilitation platform for pelvic rotations and translational motions.
* Formulated equations of motion using Lagrangian and Jacobian-based representations; built simulation to evaluate pelvic trajectories, stability envelopes, and rider balance under perturbations.

**Columbia University: LipSyncBot, Multi-Servo Viseme Control** — 02/2025–Present  
*Research Assistant (Advisor: Prof. Hod Lipson)*  
* Developed a multi-DOF robotic lip mechanism with AL20C servos and custom silicone mouth for expressive speech.
* Designed phoneme-to-viseme mapping for 44 English phonemes; created servo-angle calibration GUI for 12 lip shapes.
* Implemented Python-based lip-sync pipeline combining TTS phoneme timing with servo trajectory interpolation.

**Columbia University: 3-RRR Spherical Parallel Mechanism Ankle Rehabilitation Robot** — 02/2025–Present  
*Graduate Researcher (Advisor: Prof. Sunil K. Agrawal)*  
* Participated in design of 3-RRR spherical parallel mechanism for ankle rehabilitation (pitch–roll–yaw); contributed to dynamic modeling, Jacobian-based force mapping, workspace analysis, and passive spring compliance.

**Columbia University: Robotics Studio Course** — 02/2025–06/2025  
*Teaching Assistant (Advisor: Prof. Hod Lipson)*  
* Guided 80+ students in quadruped/bio-inspired robot design; technical support in CAD, mechanical design, simulation, and RL for legged systems.
* Assisted with PyBullet, PPO-based RL, reward tuning, and sim-to-real transfer; developed instructional examples (peak simulated running speed 25.33 m/s).

**Real-Time Blind Motion Deblurring for Humanoid Robot Vision** — 09/2023–06/2024  
*Undergraduate Thesis, Beijing University of Technology (Advisor: Prof. Naigong Yu)*  
* Developed MoUGAN (GAN + MobileNetV3 + UNet) for real-time blind motion deblurring; achieved 36.36 dB PSNR, 0.9211 SSIM, 18.79s inference on GoPro/Köhler.

**Ball-Retrieval Car with Refined A\* Algorithm** — 03/2023–06/2023  
*Programming & Embedded System Designer*  
* Improved A\* with heuristic tuning and obstacle inflation; integrated SLAM, vision-based ball detection, ROS motion control, and PID for retrieval.

**Transfer Reinforcement Learning for Gas Turbine Rotor Fault Diagnosis** — 12/2022–03/2023  
*Sole Author (accepted at IEEE SMC 2023, CCF-C)*  
* Proposed Transfer-DQN for robust fault diagnosis; M-WDCNN with ε-greedy; 98.95% and 96.91% accuracy on CWRU and domestic gas turbine datasets.

**RoboMaster Robotics Team (PIP Group), Beijing University of Technology** — 08/2022–09/2023  
*Electrical Control Lead (Advisor: Prof. Xiangyin Zhang)*  
* Led Dart System (firing control, embedded firmware, sensors, stabilization); Engineer Robot electrical architecture; Infantry chassis control and gimbal–chassis coordination; Sentry SLAM/localization; UAV control and perception. Organized training for 50+ applicants; selected 30 members.

---

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

## Additional Information

**Mapping Principal,** The 17th National College Student Smart Car Competition — 11/2021–01/2022

**Programming:** C, C++, Python  

**Software & Tools:** Python, C/C++, MATLAB, Linux/Ubuntu, ROS/ROS2, Gazebo, PyBullet, MuJoCo, Isaac Gym, OpenCV, PyTorch, TensorFlow, Reinforcement Learning, A*, PID, STM32CubeMX, FreeRTOS, Keil, UART/CAN/PWM, SolidWorks, Fusion 360, Blender, LaTeX

**Selected Awards:**
* Digital-Design-Dimensions Show (second prize provincial; National 3D Technology Application Capability Certification, Application Engineer V4)
* 2021 China Intelligent Robot Fighting and Competitive Competition (first prize provincial, humanoid autonomous fighting; third prize provincial, robot visual confrontation)
* 2022 RoboMaster University Championship (third prize)
* The 17th National College Student Smart Car Competition (third prize)
* National Undergraduate Innovation and Entrepreneurship (project approval)
* Alibaba Cloud Apsara Clouder Certification
