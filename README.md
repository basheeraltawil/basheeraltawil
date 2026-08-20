<h1 align="center">Basheer Al-Tawil</h1>

<p align="center">
  <strong>Robotics Engineer &amp; PhD Researcher — Mobile Robotics · SLAM · Computer Vision · Human-Robot Interaction</strong><br>
  Neuro-Information Technology (NIT), Otto von Guericke University Magdeburg, Germany
</p>

<p align="center">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=2E86DE&center=true&vCenter=true&width=620&lines=Robotics+Engineer+%7C+PhD+Researcher;SLAM+%C2%B7+Perception+%C2%B7+Computer+Vision;ROS2+%C2%B7+Nav2+%C2%B7+TIAGo+%C2%B7+PyTorch;Human-Aware+Navigation+%26+Interaction;Robots+that+see%2C+understand%2C+and+navigate" alt="Basheer Al-Tawil - Robotics Engineer and PhD Researcher in SLAM, Computer Vision and Human-Robot Interaction" />
</p>

<p align="center">
  <a href="https://aibomech.github.io/"><img src="https://img.shields.io/badge/Portfolio-aibomech.github.io-2E86DE?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Basheer Al-Tawil robotics portfolio website" /></a>
  <a href="https://scholar.google.com/citations?user=-06CVX4AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-Publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Basheer Al-Tawil Google Scholar publications" /></a>
  <a href="https://www.linkedin.com/in/basheeraltawil/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Basheer Al-Tawil LinkedIn profile" /></a>
  <a href="https://www.youtube.com/@AIBOMECH"><img src="https://img.shields.io/badge/YouTube-AIBOMECH-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="AIBOMECH YouTube channel - ROS2 and robotics tutorials" /></a>
</p>

<p align="center">
  <a href="https://orcid.org/0000-0002-5716-7587"><img src="https://img.shields.io/badge/ORCID-0000--0002--5716--7587-A6CE39?style=flat&logo=orcid&logoColor=white" alt="ORCID 0000-0002-5716-7587" /></a>
  <a href="https://www.researchgate.net/profile/Basheer-Al-Tawil"><img src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=flat&logo=researchgate&logoColor=white" alt="Basheer Al-Tawil ResearchGate profile" /></a>
  <a href="mailto:basheer.al-tawil@ovgu.de"><img src="https://img.shields.io/badge/Email-basheer.al--tawil%40ovgu.de-EA4335?style=flat&logo=maildotru&logoColor=white" alt="Contact Basheer Al-Tawil by email" /></a>
  <img src="https://komarev.com/ghpvc/?username=basheeraltawil&color=2E86DE&style=flat&label=Profile+Views" alt="Profile views" />
</p>

---

## About

I am a **robotics engineer and PhD researcher (Doktorand)** in the **Neuro-Information Technology (NIT)** group at **Otto von Guericke University Magdeburg, Germany**, working on **autonomous mobile robots** that perceive, reason about, and navigate human environments.

My work spans the full autonomy stack — **multi-sensor perception and fusion** (RGB-D, 2D/3D LiDAR, IMU), **visual, dynamic, and semantic SLAM**, **human action recognition** and **engagement estimation**, through to **human-aware navigation** and **LLM/VLA-driven robot task control**. Systems are validated in simulation and on real hardware, primarily the **PAL Robotics TIAGo** platform, using **ROS / ROS 2** and **Nav2**.

Published in *Sensors*, *Frontiers in Robotics and AI*, *Robotics*, and *Complex & Intelligent Systems*. Research supported by the **German Federal Ministry of Education and Research (BMBF)** and the **German Research Foundation (DFG)**.

📍 Magdeburg, Germany · 🌐 **[aibomech.github.io](https://aibomech.github.io/)** — projects, publications, and tutorials

---

## Research Focus

```mermaid
flowchart LR
    A["📷 Perception &<br/>Sensor Fusion"] --> B["🗺️ Dynamic &<br/>Semantic SLAM"]
    B --> C["🚶 Human Action &<br/>Trajectory Analysis"]
    C --> D["🤝 Human-Robot<br/>Interaction"]
    D --> E["🧭 Human-Aware Nav<br/>ROS 2 · Nav2"]
    E --> F["🦾 LLM / VLA<br/>Robot Control"]

    style A fill:#1a1a2e,stroke:#2E86DE,color:#fff
    style B fill:#1a1a2e,stroke:#2E86DE,color:#fff
    style C fill:#1a1a2e,stroke:#2E86DE,color:#fff
    style D fill:#1a1a2e,stroke:#2E86DE,color:#fff
    style E fill:#1a1a2e,stroke:#2E86DE,color:#fff
    style F fill:#1a1a2e,stroke:#2E86DE,color:#fff
```

| Area | What I work on |
| :--- | :--- |
| 📷 **Perception & Multi-Sensor Fusion** | Late-fusion of RGB-D point clouds with 2D LiDAR for robust mapping; noise filtering and degeneracy handling |
| 🗺️ **Visual, Dynamic & Semantic SLAM** | RGB-D SLAM that stays accurate when people and objects move through the scene, instead of assuming a static world |
| 🚶 **Human Action Recognition** | ResNet + Bi-LSTM with multi-head attention and optical-flow frame selection for real-time HAR in assistive robotics |
| 🤝 **Human-Robot Interaction (HRI)** | Eye-contact and engagement prediction for efficient, legible interaction between robots and people |
| 🧭 **Navigation & Motion Planning** | ROS / ROS 2 and Nav2 navigation stacks, enhanced Gmapping (EGM), adaptive resampling, real-world TIAGo deployment |
| 🦾 **LLM / VLA for Robot Control** | Integrating large language and vision-language-action models into everyday robot automation and task planning |
| 🦿 **Robot Manipulators & Kinematics** | Kinematic/kinetic analysis, trajectory planning, and grasping for robotic arms |


---

## Featured Repositories

| Repository | Description | Stack |
| :--- | :--- | :--- |
| **[HAR-ResNet-BiLSTM-Attention](https://github.com/basheeraltawil/HAR-ResNet-BiLSTM-Attention)** | Official implementation of the *Sensors* 2025 human action recognition framework — ResNet-18 spatial features, Bi-LSTM temporal modeling, multi-head attention, optical-flow frame selection | PyTorch · Python · OpenCV |
| **[Add your SLAM repo]** | Multi-sensor fusion SLAM with enhanced Gmapping (EGM), evaluated against RTAB-Map on TIAGo | ROS · C++ · Python |
| **[Add your navigation repo]** | ROS 2 / Nav2 navigation stack for human-aware mobile robot operation | ROS 2 · Nav2 · Python |

---

## Tutorials & Community

I publish practical robotics tutorials on **[YouTube @AIBOMECH](https://www.youtube.com/@AIBOMECH)** — ROS and ROS 2 fundamentals, Nav2 configuration, SLAM setup, TIAGo simulation, and computer vision for robotics. Built for engineers and researchers who want working code, not slideware.

---

## Tech Stack

**Robotics** ROS 2 · ROS 1 · Nav2 · MoveIt · Gazebo · RViz · TF2 · Behavior Trees · SMACH · Gmapping · RTAB-Map · PAL TIAGo · URDF/Xacro
**Perception & CV** OpenCV · Open3D · PCL · RGB-D processing · 2D/3D LiDAR · point cloud filtering · optical flow · semantic segmentation · object detection · pose & gaze estimation
**AI / ML** PyTorch · TensorFlow · ResNet · Bi-LSTM · multi-head attention · Transformers · LLM & VLA integration · CUDA
**Languages** Python · C++ · MATLAB · Bash
**Tooling** Docker · Git · Linux (Ubuntu) · CMake · colcon · NumPy · Pandas

<p align="center">
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Nav2-2E86DE?style=flat" alt="Nav2" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Gazebo-FF6C00?style=flat" alt="Gazebo" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white" alt="MATLAB" />
</p>

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=basheeraltawil&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" alt="Basheer Al-Tawil GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=basheeraltawil&layout=compact&theme=dark&hide_border=true&langs_count=8" height="165" alt="Most used programming languages" />
</p>

<!-- Contribution snake: generated by your own snake.yml workflow and served from your repo, so it always loads. -->
<p align="center">
  <img src="https://raw.githubusercontent.com/basheeraltawil/basheeraltawil/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution graph snake animation" />
</p>

---

## Let's Build Something

Open to **research collaborations**, **industry R&D roles**, **postdoc partnerships**, and **invited talks or tutorials** in mobile robotics, SLAM, perception, human-robot interaction, and embodied AI.

<p align="center">
  <a href="https://aibomech.github.io/"><b>Portfolio</b></a> ·
  <a href="https://scholar.google.com/citations?user=-06CVX4AAAAJ&hl=en"><b>Scholar</b></a> ·
  <a href="https://www.linkedin.com/in/basheeraltawil/"><b>LinkedIn</b></a> ·
  <a href="https://www.youtube.com/@AIBOMECH"><b>YouTube</b></a> ·
  <a href="mailto:basheer.al-tawil@ovgu.de"><b>basheer.al-tawil@ovgu.de</b></a>
</p>

---

<p align="center">
  <sub>
    <b>Research areas:</b> Robotics Engineer · PhD Researcher · Mobile Robotics · Autonomous Navigation · SLAM · Visual SLAM · Semantic SLAM · Dynamic SLAM · RGB-D SLAM · Gmapping · RTAB-Map · ROS · ROS 2 · Nav2 · MoveIt · Gazebo · Computer Vision · Multi-Sensor Fusion · LiDAR · Point Cloud Processing · Deep Learning · PyTorch · Human Action Recognition · Gaze Estimation · Engagement Prediction · Human-Robot Interaction (HRI) · Social Navigation · Motion Planning · Robot Manipulators · Vision-Language-Action (VLA) · Vision-Language Models (VLM) · Large Language Models (LLM) · Embodied AI · TIAGo · PAL Robotics · Neuro-Information Technology · OVGU · Magdeburg · Germany
  </sub>
</p>
