# Self-Balancing Robot (Work in Progress)

## 🎓 School Project
This Self-Balancing Robot is a university project designed to explore embedded systems, control theory, and robotics through real-world implementation. The project is a collaborative effort by students to apply theoretical knowledge in a hands-on engineering challenge.

## 📌 Overview
The **Self-Balancing Robot** is a two-wheeled autonomous system designed to maintain balance using feedback control mechanisms. This project explores embedded systems, control theory, and robotics through real-world implementation.

## 🔥 Features
- ✅ **Gyroscope & Accelerometer Integration** – Uses an IMU sensor for real-time motion detection.
- ✅ **PID Control Algorithm** – Maintains balance through a Proportional-Integral-Derivative (PID) controller.
- ✅ **Motor Control System** – Adjusts wheel movement dynamically to prevent falling.
- ✅ **Remote Control Functionality** – Allows manual operation via Bluetooth or Wi-Fi.

## 🎯 Project Goals
- 🏗️ Understand and apply control theory to robotics.
- ⚙️ Develop a functional real-time balancing system.
- 📈 Improve stability and response time through optimized PID tuning.
- 📡 Implement remote control and obstacle avoidance features.

## 🛠️ Tech Stack & Components
- **Microcontroller:** Arduino / Raspberry Pi / ESP32
- **Sensors:** MPU6050 (IMU)
- **Motor Drivers:** L298N or DRV8833
- **Power Supply:** Rechargeable Li-ion Battery
- **Communication:** Bluetooth / Wi-Fi Module
- **Software:** C++ (Arduino), Python (Raspberry Pi), MATLAB (for simulation)

## 🚀 Installation & Setup
### Prerequisites
- Arduino IDE / PlatformIO installed
- Required hardware components assembled
- Python & necessary libraries installed (if using Raspberry Pi)

### Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/self-balancing-robot.git
   cd self-balancing-robot
   ```
2. **Upload Code to Microcontroller:**
   - Open `robot_control.ino` in Arduino IDE.
   - Select the correct board and port.
   - Compile and upload the code.
3. **Calibrate Sensors:**
   - Run the `calibration.py` script (for Raspberry Pi users) or adjust offsets in Arduino code.
4. **Test Motor Response:**
   - Ensure motors react correctly when tilting the robot.
5. **Fine-Tune PID Parameters:**
   - Adjust `Kp`, `Ki`, and `Kd` values for optimal balancing.

## 🛣️ Roadmap
- [ ] Implement initial balancing mechanism
- [ ] Tune PID for stable control
- [ ] Integrate remote control functionality
- [ ] Add obstacle detection and avoidance
- [ ] Final testing and optimization

## 🤝 Contribution
This is a collaborative school project. Team members can contribute by:
- Improving the PID control algorithm
- Enhancing software efficiency
- Optimizing hardware design
- Testing and debugging

## 📜 License
This project is for educational purposes and not intended for commercial use.


