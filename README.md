<!-- Gesture-Controlled Game Interface README -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&pause=1000&color=36BCF7&center=true&vCenter=true&width=900&lines=✋🎮+Gesture-Controlled+Game+Interface+using+Computer+Vision;Real-Time+Human–Computer+Interaction+System;OpenCV+%7C+MediaPipe+%7C+Python" alt="Typing Animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Domain-Computer%20Vision%20%7C%20HCI-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Made%20with❤️by-Priyanka%20Asthana-ff69b4?style=for-the-badge"/>
</p>

---

## 🎥 Project Demo & Video Walkthrough (Start Here)

<p align="center">
  <a href="PUT_YOUR_VIDEO_LINK_HERE">
    <img src="https://img.shields.io/badge/▶%20Watch%20Full%20Project%20Demo-red?style=for-the-badge&logo=youtube"/>
  </a>
</p>

<p align="center">
  <sub><i>Complete walkthrough explaining system design, gesture logic, and real-time interaction pipeline.</i></sub>
</p>

---

## 🚀 Overview

This project implements a **real-time gesture-controlled gaming interface** using **computer vision and human–computer interaction (HCI)** principles.

Hand gestures captured through a webcam are processed live and translated into **system-level keyboard inputs**, enabling **hands-free control of a game** running inside an Android emulator.

The goal was not just gesture detection, but building a **robust end-to-end interaction pipeline** that connects vision, decision logic, and OS-level control in real time.

---

## 🧠 System Pipeline (High-Level)

Camera Input
   ↓
Hand Landmark Detection
   ↓
Gesture Classification
   ↓
Keyboard Event Mapping
   ↓
OS-Level Input Injection
   ↓
Game / Emulator Control
This pipeline is designed to be modular, extensible, and hardware-aware, making it suitable for experimentation with other applications beyond gaming.

## ✨ Key Features
Feature	Description
✋ Real-Time Hand Tracking	Tracks hand landmarks live using MediaPipe via CVZone
🎯 Gesture-Based Control	Interprets finger states (open palm, fist) into actions
⌨️ System-Level Input	Injects keyboard events using Python (pynput)
🎮 External App Integration	Controls a game running in an Android emulator
⚡ Low Latency Pipeline	Designed for smooth real-time interaction
🧪 Experiment-Friendly	Easy to extend with new gestures or applications

## 🧰 Tech Stack
<p align="center"> <img src="https://skillicons.dev/icons?i=python,opencv,git,vscode&theme=dark" /> </p>

## 🧰 Core Technologies

- **Python 3.10**
- **OpenCV** – video capture and frame processing
- **MediaPipe** – hand landmark detection
- **CVZone** – abstraction over MediaPipe for gesture handling
- **pynput** – OS-level keyboard event simulation

---

## 🧭 System Architecture

```mermaid
graph TD
    A[Webcam Input] --> B[OpenCV Frame Processing]
    B --> C[MediaPipe Hand Landmarks]
    C --> D[Gesture Logic]
    D --> E[Keyboard Event Mapping]
    E --> F[OS-Level Input]
    F --> G[Game / Emulator]
```
    
## 🚀 Getting Started
<p>1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/YOUR_USERNAME/gesture-controlled-game-interface.git
cd gesture-controlled-game-interface</p>
<p>2️⃣ Create Virtual Environment
bash
Copy code
python -m venv venv
venv\Scripts\Activate   # Windows </p>
<p>3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt</p>
<p>4️⃣ Run the Project
bash
Copy code
python gesture_control_hill_climb.py</p>
⚠️ Make sure the game/emulator window is in focus while running the script.

## 🧪 Gesture Mapping (Current)
<p>Gesture	Action </p>
<p>✊ Fist	Move Left 🖐 Open Palm	Move Right</p>
<p>Other / No Hand	Neutral</p>


## 👩‍💻 Author
Priyanka Asthana
<p>🎓 B.Tech (Hons) CSE | Minor in Robotics</p>
<p>📍 India</p>
