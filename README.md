# 🚗 DriveGuard: Drowsy Driver Safety System

![DriveGuard Banner](https://img.shields.io/badge/Status-Prototype-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-green)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red)
![MediaPipe](https://img.shields.io/badge/MediaPipe-AI-orange)

**DriveGuard** is a real-time, dual-signal driver monitoring system designed to detect drowsiness before it becomes dangerous. Using a standard webcam, it calculates Eye Aspect Ratio (EAR) and head tilt to trigger escalating audio-visual alarms and emergency SMS simulations.

## 🌐 Live Demo & Download
👉 **[Visit the Official Website](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)** *(Replace this link with your actual GitHub Pages link)*

## ✨ Key Features
*   **Real-Time Face Tracking:** Utilizes MediaPipe's 468 facial landmarks for highly accurate eye and head pose estimation.
*   **Dual-Signal Risk Engine:** Monitors both Eye Aspect Ratio (EAR) and Head Tilt. If *both* signals trigger simultaneously, the risk score escalates twice as fast to prevent false alarms.
*   **4-Level Escalation:** 
    *   `Level 0` (Normal) ➔ `Level 1` (Mild Beep) ➔ `Level 2` (Loud Buzzer/Vibration) ➔ `Level 3` (Critical Alarm).
*   **Emergency SMS Simulation:** If the driver reaches Level 3 and remains unresponsive for 5 seconds, the system logs an emergency event and simulates sending a GPS location to a family contact.
*   **Live Drowsiness Graph:** A dynamic, real-time graph visualizes the driver's alertness trend.

## 🛠️ Technology Stack
*   **Language:** Python 3.10+
*   **Computer Vision:** OpenCV, MediaPipe
*   **User Interface:** PyQt6
*   **Data Visualization:** PyQtGraph
*   **Audio Engine:** PyGame

## 🚀 How to Run (from source)
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
