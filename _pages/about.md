---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# Welcome!

I am a Master's student in Systems Engineering at Universiti Malaya, advised by Prof. Mahidzal Dahari.
Before that, I received my B.Eng. in Robotics Engineering from Putian University.

My research interests lie in reinforcement learning for robot locomotion, with a focus on enabling robots to acquire complex dynamic behaviours. I am broadly curious about embodied AI and actively exploring directions at the intersection of robot learning and physical systems.


# Academic Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INTRAC 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Reinforcement Learning-Controlled Quadruped Robot: From Basic Gaits to Complex Motions**

**Lin, Y.**, Dahari, M.

The 2nd International Transdisciplinary Research Conference (INTRAC 2026), Universiti Malaya. *(In Press)*
- Developed a three-stage progressive locomotion training framework for Unitree Go2, achieving Trotting, Four-Legged Synchronised Jumping, and Lateral Alternating Jumping via PPO, RSI, and AMP, with sim-to-sim validation in MuJoCo.
</div>
</div>

# News
- *Mar 2025 – Present*, Master of Systems Engineering, Universiti Malaya
- *Sep 2020 – Jun 2024*, B.Eng. in Robotics Engineering, Putian University (GPA: 86.6/100.0, Rank 3/304)

# Honors and Awards
- *2021 – 2024* First-Class Excellence Scholarship, Putian University
- *2022* National Second Prize, China Robot and Artificial Intelligence Competition
- *2023* First Prize (Special), Fujian Province Engineering Training & Innovation Competition
- *2023* Second Prize, Fujian Province Lanqiao Cup Software & IT Talent Competition
- *2023* Second Prize, Fujian Province MCU Application Design Competition
- *2021 – 2024* Outstanding Student (University-level), Putian University

# Projects

**Reinforcement Learning-Controlled Quadruped Robot: From Basic Gaits to Complex Motions**
*Oct 2025 – Present, Universiti Malaya, Advisor: Prof. Mahidzal Dahari*
- Developed a three-stage progressive locomotion training framework for Unitree Go2 using PPO in Isaac Lab across 2,048 parallel environments, achieving Trotting, Four-Legged Synchronised Jumping, and Lateral Alternating Jumping, with all policies validated via sim-to-sim transfer in MuJoCo.
- Designed stage-specific reward functions including phase-clock-based gait synchronisation, feet clearance, and flight-phase penalties, combined with velocity curriculum learning and domain randomisation across all stages.
- Implemented RSI with 8 manually designed keyframes and AMP refinement for Stage 3, confirmed by ablation study to be essential for achieving coordinated lateral alternating jumping.

**Velocity-Tracking Locomotion with AMP (Preliminary Study)**
*Jun 2025 – Aug 2025, Universiti Malaya, Advisor: Prof. Mahidzal Dahari*

To validate the feasibility of AMP on the Unitree Go2, I implemented a velocity-tracking policy in Isaac Lab using the open-source `legged_control` dataset.

- **Key Finding:** Learned behaviour is fundamentally constrained by reference data coverage — a forward-only dataset failed to generalise to backward locomotion, highlighting that dataset balance is a critical design factor in AMP-based training.

**Design of a Multifunctional Foot Bath Robot Based on Microcontroller** (Bachelor's Thesis)
*Nov 2023 – Apr 2024, Putian University, Advisor: Lian Jialing*
- Independently designed and implemented a full-stack embedded system based on STM32F103RCT6, integrating 8 subsystems including motion control, temperature regulation, UWB positioning, and remote APP control.
- Developed PID-based temperature control (±0.5°C accuracy) with DS18B20 sensor and trapezoidal acceleration/deceleration algorithm for stepper motor motion control via PWM.
- Achieved 3 cm UWB positioning accuracy; designed mechanical structure independently using SolidWorks.

**YOLOv8-Based Automated Waste Classification and Sorting System**
*Oct 2022 – Mar 2023, Putian University, Advisor: Chen Min — First Prize (Special), Fujian Province Engineering Training & Innovation Competition*
- Developed an automated waste sorting system using a dual-conveyor belt mechanism with YOLOv8-based real-time classification of 4 waste categories deployed on Raspberry Pi.
- Implemented STM32-controlled servo routing to direct classified waste into corresponding bins based on detection results.

**Autonomous Navigation and Precision Shooting Robot**
*Mar 2022 – Aug 2022, Putian University, Advisor: Zhao Yawen — National Second Prize, China Robot and Artificial Intelligence Competition*
- Developed autonomous navigation and target shooting across 5 waypoints (3 shooting positions + start/end) on a competition-provided platform using ROS1.
- Calibrated waypoint coordinates and actuation timing to achieve precise in-zone positioning and water balloon launching at each target.

# Skills
- **Programming:** Python, C/C++, MATLAB
- **Tools & Frameworks:** Isaac Lab, MuJoCo, PyTorch, ROS1, ROS2, Git, Linux, STM32, SolidWorks
- **Languages:** English (PTE Academic: 58), Chinese (Native)
