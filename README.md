# Lunar-Inflatable-Habitat-Multi-Gripper-Manipulator

This repository summarizes the core design ideas of a **multi-gripper end-effector system** for a lunar inflatable habitat construction robot.  
The project focuses on enabling a single robotic arm to handle **tools, samples, structural parts, and instrument modules** through interchangeable grippers.

---

## 1. Overview

Future lunar habitats benefit from **inflatable structures** and **in-situ resource utilization (ISRU)**.  
Construction tasks are diverse, so one fixed end-effector is useless.  
We propose a **modular tool-changing system** supporting multiple specialized grippers:

- **Adaptive Gripper** – flexible 4-finger rope-pulley mechanism for irregular samples  
- **Tool Gripper** – for screw-driving, pipe alignment, and precise installation  
- **Instrument Extraction Gripper** – mates with standardized extraction heads  
- **Cargo Box Gripper** – for transport of equipment cases (concept stage)

A dedicated **gripper docking station** allows quick switching during missions.

---

## 2. System Architecture

Main components:

- **Gripper Library (Dock Station)**  
  Quick mechanical interface for mounting/detaching grippers.

- **Four Types of End-Effectors**  
  Each designed for a specific lunar construction scenario.

- **Sensing & Perception**  
  - Vision for object recognition & pose estimation  
  - Force/pressure sensors for safe gripping  
  - Mechanical dust-resistant layouts for lunar regolith

---

## 3. Typical Workflow

1. Robot identifies the target object.  
2. Selects a suitable gripper from the docking station.  
3. Executes the action:
   - Picking irregular samples  
   - Installing screws  
   - Handling instruments  
   - Transporting cargo cases  
4. Sensors provide continuous feedback to avoid misalignment or damage.
<img width="1545" height="867" alt="image" src="https://github.com/user-attachments/assets/93c48f41-75cf-494d-a693-9550d7725668" />
<img width="1575" height="916" alt="image" src="https://github.com/user-attachments/assets/0dd40f9e-8cbb-4ade-af2d-201524e8bc4d" />
<img width="1578" height="882" alt="image" src="https://github.com/user-attachments/assets/eee4b982-6f88-40f4-a22c-8417269d8143" />
<img width="1361" height="661" alt="image" src="https://github.com/user-attachments/assets/b8bf6d7f-2994-405b-99d0-611a3a982530" />
<img width="1106" height="715" alt="image" src="https://github.com/user-attachments/assets/3cdda5d9-ce4c-4b1f-b831-27e2f83300ed" />

---

## 4. Current Limitations & Next Steps

- Instrument gripper still needs a **better self-alignment mechanism**.  
- Cargo-box gripper requires further structural verification.  
- Exploring new “**transformable palm**” concepts inspired by:
  - cube-like multi-face designs  
  - foldable / transformer-style mechanisms  


