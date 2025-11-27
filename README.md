<h1 align="center">🔧 Arduino Ultrasonic Radar System</h1>

<p align="center">
A real-time object detection radar system using Arduino, ultrasonic sensing, and Processing GUI visualization.
</p>

---

<p align="center">
  
  <img src="https://img.shields.io/badge/Platform-Arduino-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Language-C%2B%2B%20%7C%20Processing-green?style=flat-square">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square">
 
</p>

---

## 📘 Overview

This project simulates a real-world radar scanning system. The **HC-SR04 Ultrasonic sensor** is mounted on a servo motor and sweeps between **15°–165°**, measuring object distance. Values are sent via serial communication to a **Processing GUI**, which visualizes the radar sweep on screen.

---

## 🛠️ Features

- Continuous 180° scanning motion  
- Real-time distance measurement  
- Live radar visualization GUI  
- Detects objects up to ~40cm  
- Smooth servo sweep motion  

---

## 📦 Requirements

### 🧰 Hardware

| Component | Qty |
|----------|-----|
| Arduino Uno | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| SG90 Servo Motor | 1 |
| Breadboard (optional) | 1 |
| Jumper wires | As needed |
| USB cable | 1 |
| (Optional) External 5V supply | 1 |


### 💻 Software

- Arduino IDE  
- Processing IDE  
- CH340 / Arduino USB drivers  
- (Optional) Git / GitHub Desktop  

### 📚 Libraries Used

| Platform | Library |
|----------|---------|
| Arduino | `Servo.h` (built-in) |
| Processing | `processing.serial.*` (built-in) |

---


