<div align="center">

# SteamedClams: Team Organization & Division of Labor

<img src="https://img.shields.io/badge/TEAM-STEAMED_CLAMS-ff69b4?style=for-the-badge" alt="Team Name">
<img src="https://img.shields.io/badge/COURSE-AAE5303-1f77b4?style=for-the-badge" alt="Course">
<img src="https://img.shields.io/badge/ROLE-COLLABORATION-5cb85c?style=for-the-badge" alt="Role">

<h3>Robust Control Technology in Low-Altitude Aerial Vehicles</h3>

<i>A Multi-Disciplinary Engineering Collaboration</i>

<br>
</div>

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Engineering Division of Labor](#engineering-division-of-labor)
3. [Workflow & Integration](#workflow--integration)
4. [Links](#links11)

---

<span id="project-overview"></span>
## 🎯 Project Overview
The **SteamedClams** team is a cross-disciplinary engineering group focused on robotics vision and UAV environmental perception technologies. Our core mission is to bridge the gap between 3D geometric reconstruction and semantic environmental perception. This repository documents our agile development roles and specific contributions to the AAE5303 project.

---

<span id="engineering-division-of-labor"></span>
## 🤝 Engineering Division of Labor

We have categorized our contributions into **Development (Engineering)** and **Technical Defense (Presentation)** to ensure every module is robustly built and clearly explained.

| Project Module | Engineering & Execution | Technical Defense (Presentation) |
| :--- | :--- | :--- |
| **PART I: SLAM & Evaluation** | **YANG Yuxin (Lead)** <br> 🔹 *Core algorithm execution, trajectory generation, and VO parameter tuning.* <br><br> **CHEN Yushan** <br> 🔹 *ROS workspace configuration, environment deployment, and dependency management.* |  🎙️ **YANG Yuxin** <br> *Part1. Scene Definition & Visual SLAM* |
| **PART II: 3D Reconstruction** | **WANG Shiwei (Lead)** <br> 🔹 *End-to-end implementation of 3D Gaussian Splatting and parameter tuning.* |  🎙️ **WANG Shiwei** <br> *Part2. 3D Scene Reconstruction* |
| **PART III: Semantic Segmentation** | **CHEN Yushan (Lead)** <br> 🔹 *Model training pipeline, optimization direction (custom class weights), and loss function design.* <br><br> **YANG Yuxin** <br> 🔹 *Data preprocessing (DataLoader & Augmentation) and visualization.* |  🎙️ **CHEN Yushan** <br> *Part3. Semantic segmentation* <br> *Part4. System Evaluation & Global Retrospective* |

---

<span id="workflow--integration"></span>
## 🔄 Workflow & Integration

Our team follows a robust **"Upstream Dependency + Parallel Execution"** strategy:
1. **Phase 1: Upstream Development**: CHEN Yushan and YANG Yuxin spearheaded PART I, completing the deployment of Visual Odometry, trajectory estimation, and core data extraction.
2. **Phase 2: Data Handoff & Parallel Execution**: The poses and point cloud data successfully generated in PART I were handed over to WANG Shiwei. Subsequently, PART II (3D Reconstruction by WANG) and PART III (Semantic Segmentation by CHEN & YANG) entered an intensive parallel development phase.
3. **Phase 3: Unified Integration**: All independent engineering outputs were finally integrated into the presentation framework designed by **CHEN Yushan** to ensure a highly cohesive technical story for the final defense.

---

<span id="links11"></span>
## ✈️ Links

- **VO:** [https://github.com/YuxinYang2002/AAE5303_group_project_VO]
- **Opensplating:** [https://github.com/wswjackie2003-hub/AAE5303_opensplating]
- **U-net:** [https://github.com/cclinko/AAE5303_group_project_u-net]

---

<div align="center">
<i>" SteamedClams ZHENBANG！"</i>
</div>
