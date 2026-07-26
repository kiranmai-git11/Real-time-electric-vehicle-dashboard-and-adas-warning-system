# 🚗 Real-Time Electric Vehicle Dashboard and ADAS Warning System

> **Embedded Systems Internship Project** developed using **STM32F103C8T6 Blue Pill** to simulate a Real-Time Electric Vehicle Dashboard integrated with Advanced Driver Assistance System (ADAS) features.

---

## 📸 Dashboard Preview

<p align="center">
<img src="Images/dashboard.png" width="900">
</p>

---

## 📖 Project Overview

This project demonstrates the implementation of a **Real-Time Electric Vehicle Dashboard** integrated with **Advanced Driver Assistance System (ADAS)** using the STM32F103C8T6 Blue Pill microcontroller.

The dashboard continuously monitors vehicle parameters such as speed, battery level, motor temperature, accelerator position, brake status, and torque while simultaneously providing ADAS safety warnings through ultrasonic sensor-based obstacle detection.

Sensor values are processed by the STM32 microcontroller and transmitted through UART to a Python-based graphical dashboard that visualizes the vehicle status in real time.

---

## ✨ Features

- 🚗 Real-Time Speed Monitoring
- 🔋 Battery State of Charge (SOC)
- 🌡 Motor Temperature Monitoring
- ⚡ Torque Calculation
- 🚦 Accelerator & Brake Monitoring
- 📈 Live Speed History Graph
- 🚧 Forward Collision Warning
- 🚙 Bird's Eye ADAS View
- 🔊 Multi-Level Alarm System
- 📡 UART Communication
- 🐍 Python GUI Dashboard

---

## 🛠 Hardware

- STM32F103C8T6 Blue Pill
- HC-SR04 Ultrasonic Sensors
- Potentiometers
- LEDs
- Buzzer

---

## 💻 Software

- STM32CubeMX
- STM32CubeIDE
- Embedded C
- Python
- PICSimLab
- PySerial
- Virtual Serial Port

---

## 📷 Project Images

### EV Dashboard

![Dashboard](Images/dashboard.png)

---

### STM32CubeMX Configuration

![STM32CubeMX](Images/stm32cubemx.jpg)

---

### PICSimLab Simulation

![PICSimLab](Images/picsimlab-sensors.jpg)

---

### Blue Pill Simulation

![Blue Pill](Images/bluepill.jpg)

---

### UART Communication

![UART](Images/uart-output.jpg)

---

## 🚀 Working Flow

Potentiometers → STM32 ADC → Embedded C Processing → UART → Python Dashboard → ADAS Alerts

---

## 🎯 Learning Outcomes

- Embedded C Programming
- STM32 Development
- UART Communication
- ADC Programming
- Sensor Interfacing
- Automotive Embedded Systems
- Python GUI Development

---

## 👩‍💻 Author

**Kiranmai Kandhari**

B.Tech – Electronics and Communication Engineering

GitHub:
https://github.com/kiranmai-git11

---

⭐ If you like this project, don't forget to give it a **Star**.
