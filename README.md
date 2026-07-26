# 🚗 Real-Time Electric Vehicle Dashboard and ADAS Warning System

> An Embedded Systems Internship Project developed using the **STM32F103C8T6 Blue Pill Microcontroller** to simulate a real-time Electric Vehicle (EV) Dashboard integrated with basic Advanced Driver Assistance System (ADAS) features.

![STM32](https://img.shields.io/badge/STM32-Blue%20Pill-blue)
![Embedded C](https://img.shields.io/badge/Language-Embedded%20C-success)
![Python](https://img.shields.io/badge/Python-Dashboard-yellow)
![UART](https://img.shields.io/badge/Communication-UART-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📖 Overview

Modern Electric Vehicles rely on an Electronic Control Unit (ECU) to continuously monitor vehicle parameters and provide safety assistance.

This project simulates that concept using the **STM32F103C8T6 Blue Pill** microcontroller as the learning ECU. Sensor values are processed in real time and transmitted via UART to a Python-based dashboard, which displays live vehicle information and ADAS warnings.

This project was developed as part of my **Embedded Systems Internship at Emertxe Information Technologies, Bangalore.**

---

# 🎯 Objectives

- Simulate an Electric Vehicle Dashboard
- Implement basic ADAS features
- Read analog sensor values using ADC
- Process sensor data using STM32F103C8T6
- Transmit telemetry via UART
- Display real-time data using a Python dashboard
- Learn practical Automotive Embedded System concepts

---

# ✨ Features

## EV Dashboard

- Real-Time Vehicle Speed
- Battery State of Charge (SOC)
- Motor Temperature Monitoring
- Estimated Driving Range
- Drive Mode Simulation

## ADAS Features

- Forward Collision Detection
- Blind Spot Detection
- Time-To-Collision (TTC)
- Multi-Level Warning System
- Visual and Audible Alerts

---

# 🛠 Hardware Used

- STM32F103C8T6 Blue Pill
- 4 Potentiometers
- 3 HC-SR04 Ultrasonic Sensors
- LEDs
- Buzzer

---

# 💻 Software Used

- STM32CubeMX
- STM32CubeIDE
- PICSimLab
- Python
- PySerial
- Tera Term
- Virtual Serial Port (VSP)

---

# ⚙️ Working Principle

1. Potentiometers simulate:
   - Accelerator
   - Brake
   - Battery SOC
   - Motor Temperature

2. STM32 ADC converts analog values into digital data.

3. STM32 executes:
   - EV Control Logic
   - ADAS Control Logic

4. Ultrasonic sensors detect obstacles.

5. Processed telemetry is transmitted through UART.

6. Python receives the serial data and updates the dashboard in real time.

---

# 📊 System Architecture

```
Potentiometers
        │
        ▼
ADC Conversion
        │
        ▼
STM32F103C8T6
        │
 ┌──────┴────────┐
 │               │
 ▼               ▼
EV Logic     ADAS Logic
        │
        ▼
UART Communication
        │
        ▼
Python Dashboard
```

---

# 🚨 Alarm Logic

| Condition | Indicator | Response |
|-----------|-----------|----------|
| Normal | 🟢 Green LED | Normal operation |
| Warning | 🟡 Yellow LED | Driver Warning |
| Critical | 🔴 Red LED + Buzzer | Immediate Action Required |

---

# 📈 Technologies

- Embedded C
- STM32 HAL
- UART Communication
- ADC
- Sensor Interfacing
- Python
- PySerial
- PICSimLab

---

# 📂 Project Structure

```
Core/
Drivers/
Debug/
Python.py
ev_dash.ioc
STM32F103C8TX_FLASH.ld
README.md
```

---

# 🚀 How to Run

1. Open the STM32 project in STM32CubeIDE.
2. Build the firmware.
3. Connect the UART interface.
4. Run the Python dashboard.
5. Simulate sensor values using potentiometers.
6. Observe live dashboard updates and ADAS warnings.

---

# 📷 Screenshots

Add screenshots here:

- Dashboard
- PICSimLab Simulation
- UART Output
- STM32CubeIDE

---

# 🎓 Learning Outcomes

Through this project I gained practical experience in:

- Embedded C Programming
- STM32 Development
- UART Communication
- ADC Programming
- Sensor Interfacing
- Python Integration
- Automotive Embedded Systems

---

# 👩‍💻 Author

**K. Kiranmai**

B.Tech – Electronics and Communication Engineering

Megha Institute of Engineering and Technology for Women

GitHub: https://github.com/kiranmai-git11

---

# 🙏 Acknowledgement

This project was developed during my **Embedded Systems Internship at Emertxe Information Technologies, Bangalore**.

Special thanks to the mentors at Emertxe for their guidance and support throughout the internship.

---

⭐ If you found this project helpful, please consider giving it a Star.
