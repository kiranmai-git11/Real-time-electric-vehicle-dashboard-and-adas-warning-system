# 🚗 Real-Time Electric Vehicle Dashboard and ADAS Warning System

> **Embedded Systems Internship Project** developed using the **STM32F103C8T6 Blue Pill Microcontroller** to simulate a Real-Time Electric Vehicle Dashboard integrated with **Advanced Driver Assistance System (ADAS)** features.

---

## 📸 Dashboard Preview

<p align="center">
  <img src="ES%20images/dashboard.png" alt="EV Dashboard" width="900">
</p>

---

# 📖 Project Overview

This project demonstrates the implementation of a **Real-Time Electric Vehicle Dashboard** integrated with **Advanced Driver Assistance System (ADAS)** using the **STM32F103C8T6 Blue Pill** microcontroller.

The system continuously monitors important vehicle parameters such as **Speed, Battery State of Charge (SOC), Motor Temperature, Accelerator Position, Brake Status, and Torque**. It also provides **ADAS safety warnings** using ultrasonic sensor-based obstacle detection.

Sensor data is processed by the STM32 microcontroller and transmitted through **UART** to a **Python-based graphical dashboard**, where the vehicle status is displayed in real time.

---

# 🎯 Objectives

- Simulate a Real-Time Electric Vehicle Dashboard
- Monitor important EV parameters
- Implement basic ADAS warning features
- Read analog sensor values using ADC
- Process sensor data using STM32
- Transmit telemetry through UART
- Visualize data on a Python dashboard

---

# ✨ Features

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

# 🛠 Hardware Used

- STM32F103C8T6 Blue Pill
- HC-SR04 Ultrasonic Sensors
- Potentiometers
- LEDs
- Buzzer

---

# 💻 Software Used

- STM32CubeMX
- STM32CubeIDE
- Embedded C
- Python
- PICSimLab
- PySerial
- Virtual Serial Port (VSP)

---

# ⚙️ System Architecture

```text
Potentiometers
      │
      ▼
ADC Conversion
      │
      ▼
STM32F103C8T6 Blue Pill
      │
 ┌────┴────┐
 │         │
 ▼         ▼
EV Logic  ADAS Logic
      │
      ▼
UART Communication
      │
      ▼
Python Dashboard
```

---

# 🚀 Working Flow

1. Potentiometers simulate vehicle parameters.
2. STM32 reads analog values through ADC.
3. Embedded C processes the sensor data.
4. Ultrasonic sensors detect nearby obstacles.
5. UART sends processed data to the PC.
6. Python receives the data and updates the dashboard.
7. ADAS warnings are displayed whenever necessary.

---

# 📷 Project Images

## EV Dashboard

![Dashboard](ES%20images/dashboard.png)

---

## STM32CubeMX Configuration

![STM32CubeMX](ES%20images/stm32cubemx.jpg)

---

## PICSimLab Simulation

![PICSimLab](ES%20images/picsimlab-sensors.jpg)

---

## STM32 Blue Pill Simulation

![Blue Pill](ES%20images/bluepill.jpg)

---

## UART Communication

![UART Output](ES%20images/uart-output.jpg)

---

# 📂 Project Structure

```text
ev_dash
│
├── Core/
├── Drivers/
├── Debug/
├── ES images/
│   ├── dashboard.png
│   ├── stm32cubemx.jpg
│   ├── picsimlab-sensors.jpg
│   ├── bluepill.jpg
│   └── uart-output.jpg
│
├── Python.py
├── ev_dash.ioc
├── README.md
```

---

# 🚀 How to Run

1. Open the project in **STM32CubeIDE**.
2. Build and flash the firmware to the STM32 Blue Pill.
3. Configure the UART communication.
4. Run the Python dashboard application.
5. Simulate sensor values using PICSimLab.
6. Observe the real-time dashboard and ADAS alerts.

---

# 🎓 Learning Outcomes

This project helped me gain practical experience in:

- Embedded C Programming
- STM32 Microcontroller Development
- ADC Programming
- UART Communication
- Sensor Interfacing
- Python GUI Development
- Automotive Embedded Systems
- EV Dashboard Design
- ADAS Fundamentals

---

# 🔮 Future Enhancements

- GPS Integration
- CAN Bus Communication
- IoT Cloud Connectivity
- Battery Management System (BMS)
- Lane Departure Warning
- Driver Drowsiness Detection
- Mobile Application Integration

---

# 👩‍💻 Author

**Kiranmai Kandhari**

🎓 B.Tech – Electronics and Communication Engineering

💻 GitHub: https://github.com/kiranmai-git11

---

# 🙏 Acknowledgement

This project was developed as part of my **Embedded Systems Internship at Emertxe Information Technologies**.

I sincerely thank my mentors and the Emertxe team for their continuous guidance and support throughout the internship.

---

⭐ **If you found this project interesting, please consider giving it a Star on GitHub!**


