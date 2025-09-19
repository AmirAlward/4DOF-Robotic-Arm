# 🤖 4DOF Robotic Arm with ESP32 and Web Control

A 4DOF robotic arm built with **3D-printed parts**, powered by an **ESP32**, and controlled through a custom **web interface**.  
The project demonstrates the integration of **embedded systems, IoT, and mechanical design** into a functional robotic platform.

---

## 🔧 Features
- WiFi-enabled control via ESP32  
- Custom web interface (HTML, CSS, JavaScript)  
- Real-time servo control (Base, Shoulder, Elbow, Wrist, Gripper)  
- Record and playback of motion sequences  
- Battery-powered with buck converter  
- Modified gear mechanism for smoother motion  

---

## 🛠️ Tech Stack
**Hardware**  
- ESP32  
- Servo motors (x5)  
- Battery + buck converter  
- 3D-printed arm components (Fusion 360 design, sliced for 3D printing)  

**Software**  
- Arduino (C++ for ESP32)  
- Web technologies (HTML, CSS, JS)  
- Fusion 360 (design)  
- Cura / slicer tools (3D printing prep)  

---

## 📂 Repository Structure
4DOF-Robotic-Arm/
├── software/ # ESP32 firmware (Arduino code)
├── hardware/ # 3D design files (.f3d, .stl)
├── docs/ # Documentation, diagrams, notes
├── README.md # This file

yaml
Copy code

---

## 🚀 Getting Started

### 1️⃣ Hardware Setup
1. 3D print the parts from `/hardware` and assemble the arm.  
2. Connect servo motors to ESP32 pins (defined in code).  
3. Power via battery + buck converter.  

### 2️⃣ Software Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/AmirAlward/4DOF-Robotic-Arm.git
   cd 4DOF-Robotic-Arm/software
Open the sketch in Arduino IDE.

Install required libraries:

ESP32Servo

ESPAsyncWebServer

AsyncTCP

Flash the ESP32.

3️⃣ Control the Arm
ESP32 creates a WiFi hotspot.

Connect to it and open the provided IP in a browser.

Use the web UI to move joints, record, and replay actions.

🎥 Demo
📹 Video coming soon

📖 Background
The initial design was inspired by this project video, but the mechanical parts were modified in Fusion 360, and all code was written from scratch.
The project also served as a practical application of Embedded Systems & Interfacing and Project Management coursework.

👨‍💻 Author
Amir Alward

🎓 Mechatronics Engineering Student

🌍 Based in Yemen

💡 Passionate about robotics, IoT, and automation

