# Line Following Robot 🚗🤖

[![Arduino](https://img.shields.io/badge/Made%20with-Arduino-blue?logo=arduino)](https://www.arduino.cc/)
[![C++](https://img.shields.io/badge/Language-C++-brightgreen?logo=cplusplus)](https://isocpp.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple **Arduino-based Line Following Robot** that uses **IR sensors** to detect a path and controls two DC motors via an H-bridge motor driver.  
This project demonstrates **autonomous navigation** with PWM speed control and is ideal for robotics beginners and competitions.  

---

## 📂 Repository Structure
- `line_follower.ino` → Arduino C++ source code  
- `wiring_diagram.png` → Circuit/wiring diagram  
- `README.md` → Documentation (this file)  

---

## 🛠️ Components
- Arduino Uno (or compatible board)  
- L293D / L298N Motor Driver  
- 2 × IR Sensors  
- 2 × DC Motors + Wheels  
- 1 × Chassis + Battery Pack (7.4V–12V recommended)  
- Jumper wires  

---

## ⚡ How It Works
- **Both sensors LOW** → Robot moves forward  
- **Left HIGH, Right LOW** → Robot turns left  
- **Right HIGH, Left LOW** → Robot turns right  
- **Both HIGH** → Robot stops  

This logic can be extended for more advanced navigation.  

---

## 📷 Circuit Diagram
  ![Line Following Robot (Wearing Diagram)](https://github.com/user-attachments/assets/686953c1-c36e-45d9-beb1-212f1f9383e5)


---

## 🚀 Getting Started

### 1️⃣ Install Arduino IDE
Download from [Arduino IDE](https://www.arduino.cc/en/software).

### 2️⃣ Clone this Repository
```bash
git clone https://github.com/YOUR-USERNAME/line-following-robot.git
cd line-following-robot
