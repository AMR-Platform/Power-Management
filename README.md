# 🔋 Power Management System for AMR Platform

This repository contains the design files and documentation for the **Power Distribution Module** developed for an **Autonomous Mobile Robot (AMR)** platform. The focus is on **compact**, **reliable**, and **high-current-capable** power delivery to all major subsystems.

---

## ⚙️ Overview

In mobile robotic platforms, reliable power management is essential for ensuring safe and efficient operation. This project introduces a custom-designed PCB to manage power distribution from a high-voltage battery source to multiple modules including:

- Motor drivers (6–7 A each)
- Onboard computer (e.g., Jetson Nano)
- Microcontroller unit (MCU)
- Sensors (e.g., LiDAR)

---

## 🛠️ Design Features

- **High-Current Copper Pours**  
  Top-layer copper pours are used for high-current paths (e.g., motors) to ensure thermal performance and reduce voltage drops.

- **Dedicated Ground Plane**  
  A full **bottom-layer ground plane** provides a low-impedance return path, minimizing noise and improving signal integrity.

- **Compact PCB Layout**  
  The board is designed to fit within the tight mechanical constraints of a mobile robot chassis while maximizing current delivery and thermal efficiency.

- **Modular Connectivity**  
  Outputs are routed to standard connectors for ease of wiring and modularity.

---

## 🔋 Input & Output Specs

- **Input Voltage:** 22.2V (from 2× 11.1V LiPo in series)
- **Total Current Support:** Up to 20 A combined
- **Power Paths:**
  - Motors: 2 × 6–7 A
  - Jetson Nano: 5 A
  - LiDAR: 2 A
  - MCU: 2 A

---

## 📂 Contents

- `PCB/` – Altium project files, schematics and board layout
- `Documentation/` – Design overview, block diagrams, and power budget
- `Images/` – Renders and pictures of the assembled board

---

## 📸 Preview

<p align="left">
  <img src="images/Screenshot 2025-07-25 191852" alt="Schematic Diagram" width="400"/>
  <br/>
  <em>Top View – Schematic Diagram</em>
</p>

<p align="left">
  <img src="images/Screenshot 2025-07-25 184605" alt="Top Layer" width="400"/>
  <br/>
  <em>Top View – Top Layer</em>
</p>

<p align="left">
  <img src="images/Screenshot 2025-07-25 184616" alt="Bottom Layer" width="400"/>
  <br/>
  <em>Top View – Bottom Layer</em>
</p>
