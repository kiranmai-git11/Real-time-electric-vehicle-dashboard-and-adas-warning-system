# 🚗 Real-Time Electric Vehicle Dashboard and ADAS Warning System

> An Embedded Systems Internship Project developed using the **STM32F103C8T6 Blue Pill Microcontroller** to simulate a Real-Time Electric Vehicle (EV) Dashboard integrated with **Advanced Driver Assistance System (ADAS)** features.

<p align="center">
  <img src="Images/dashboard.png" alt="EV Dashboard" width="900">
</p>

---

## 📖 Project Overview

The **Real-Time Electric Vehicle Dashboard and ADAS Warning System** is an embedded systems project that simulates the functionality of a modern Electric Vehicle dashboard along with basic Advanced Driver Assistance System (ADAS) features.

The system uses the **STM32F103C8T6 Blue Pill** microcontroller to acquire and process sensor data in real time. Vehicle parameters such as speed, battery level, motor temperature, accelerator position, brake status, and torque are monitored continuously.

The processed data is transmitted via **UART** to a **Python-based graphical dashboard**, which displays live vehicle information and safety alerts. Ultrasonic sensors simulate obstacle detection and trigger ADAS warnings when objects are detected within predefined safety distances.

---

## 🎯 Objectives

- Design a Real-Time Electric Vehicle Dashboard.
- Simulate EV parameters using embedded hardware.
- Implement basic ADAS warning functionality.
- Read analog sensor values using ADC.
- Process sensor data using the STM32 microcontroller.
- Communicate data using UART.
- Display live vehicle information using a Python GUI.

---

## ✨ Features

- 🚗 Real-Time Speed Monitoring
- 🔋 Battery State of Charge (SOC)
- 🌡️ Motor Temperature Monitoring
- ⚡ Torque Monitoring
- 🚦 Accelerator Position Monitoring
- 🛑 Brake Status Monitoring
- 📈 Live Speed History Graph
- 🚧 Forward Collision Warning
- 🚙 Bird's Eye ADAS View
- 🔊 Multi-Level Alarm System
- 📡 UART Communication
- 🐍 Python-Based Dashboard

---

## 🛠️ Hardware Components

- STM32F103C8T6 Blue Pill Microcontroller
- HC-SR04 Ultrasonic Sensors
- Potentiometers
- LEDs
- Buzzer

---

## 💻 Software Used

- STM32CubeMX
- STM32CubeIDE
- Embedded C
- Python
- PICSimLab
- PySerial
- Virtual Serial Port (VSP)

---

## ⚙️ System Architecture

```text
Potentiometers
       │
       ▼
ADC Conversion
       │
       ▼
STM32F103C8T6 Blue Pill
       │
 ┌─────┴────────┐
 │              │
 ▼              ▼
EV Logic     ADAS Logic
       │
       ▼
UART Communication
       │
       ▼
Python Dashboard
```

---

## 🔄 Working Principle

1. Potentiometers simulate vehicle parameters such as accelerator, brake, battery level, and motor temperature.
2. The STM32 microcontroller reads these analog values using ADC.
3. Embedded C firmware processes the sensor data.
4. Ultrasonic sensors detect nearby obstacles.
5. Vehicle information and warning messages are transmitted via UART.
6. The Python dashboard displays live EV data and ADAS alerts in real time.

---

## 📷 Project Images

### 🚗 EV Dashboard

![Dashboard](Images/dashboard.png)

---

### ⚙️ STM32CubeMX Configuration

![STM32CubeMX](Images/stm32cubemx.jpg)

---

### 🔌 PICSimLab Simulation

![PICSimLab](Images/picsimlab-sensors.jpg)

---

### 💻 STM32 Blue Pill Simulation

![Blue Pill](Images/bluepill.jpg)

---

### 📡 UART Communication

![UART Output](Images/uart-output.jpg)

---

## 📂 Project Structure

```text
Real-time-electric-vehicle-dashboard-and-adas-warning-system
│
├── Core/
├── Drivers/
├── Debug/
├── Images/
│   ├── dashboard.png
│   ├── stm32cubemx.jpg
│   ├── picsimlab-sensors.jpg
│   ├── bluepill.jpg
│   └── uart-output.jpg
│
├── Python.py
├── ev_dash.ioc
├── README.md
└── ...
```

---

## 🚀 Getting Started

1. Open the project using **STM32CubeIDE**.
2. Build and flash the firmware to the STM32F103C8T6 Blue Pill.
3. Configure UART communication.
4. Run the Python dashboard application.
5. Simulate sensor inputs using PICSimLab.
6. Observe live dashboard updates and ADAS warning messages.

---

## 📈 Applications

- Electric Vehicle Dashboard Simulation
- Automotive Embedded Systems
- ADAS Concept Demonstration
- Embedded Systems Learning
- Academic and Internship Projects

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Embedded C Programming
- STM32 Microcontroller Programming
- ADC Configuration
- UART Communication
- Sensor Interfacing
- Python GUI Development
- PICSimLab Simulation
- Automotive Embedded Systems
- Electric Vehicle Dashboard Design
- ADAS Fundamentals

---

## 🔮 Future Enhancements

- CAN Bus Communication
- GPS Integration
- IoT Cloud Connectivity
- Battery Management System (BMS)
- Lane Departure Warning
- Driver Drowsiness Detection
- Mobile Application Support

---

## 👩‍💻 Author

**Kiranmai Kandhari**

**B.Tech – Electronics and Communication Engineering**

🔗 GitHub: https://github.com/kiranmai-git11

---

## 🙏 Acknowledgement

This project was developed during my **Embedded Systems Internship at Emertxe Information Technologies**.

I sincerely thank my mentors and the Emertxe team for their continuous guidance and support throughout the internship.

---

## ⭐ Support

If you found this project helpful or interesting, please consider giving it a **⭐ Star** on GitHub.
