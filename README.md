# 🔥 IoT-Enabled Smart Gas Leakage Monitoring System

![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Sensor](https://img.shields.io/badge/Sensor-MQ--2%20%7C%20DHT11-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

> An embedded IoT safety system that continuously monitors combustible gas concentration with user-configurable thresholds, real-time web monitoring, audible alerts, and automatic relay-triggered solenoid valve shutdown.

---

## 📌 Features

- 🔍 Real-time gas concentration monitoring using MQ-2 sensor
- 🌡️ Temperature & humidity sensing via DHT11
- ⚙️ User-configurable safety threshold via keypad
- 📺 Local 16×2 LCD display for live readings
- 🌐 Local web interface over Wi-Fi (no cloud needed)
- 🔔 Buzzer alert on abnormal gas levels
- 🔌 Automatic solenoid valve shutdown via relay on critical levels

---

## 🖼️ Hardware Prototype

![Prototype](MINI%20PROJECT.jpeg)

---

## 🧰 Hardware Components

| Component | Function |
|-----------|----------|
| ESP32 Microcontroller | Central processing & Wi-Fi |
| MQ-2 Gas Sensor | Combustible gas detection |
| DHT11 Sensor | Temperature & humidity monitoring |
| 3×4 Keypad | User threshold input |
| 16×2 LCD (I2C) | Local display |
| Relay Module | Switching control |
| Solenoid Valve | Automatic gas flow shutdown |
| Buzzer | Audible alert |

---

## 🔁 3-Level Safety Logic

| Level | Condition | Action |
|-------|-----------|--------|
| ✅ Safe | Gas < 40% of threshold | Monitor only |
| ⚠️ Warning | Gas approaching threshold | Buzzer ON |
| 🚨 Critical | Gas > threshold | Buzzer ON + Valve CLOSED |

---

## 👩‍💻 Author

**Arshiya Tabassum**
B.Tech EEE | Vardhaman College of Engineering, Hyderabad
Secretary, IEEE IES Chapter
📧 arshiyahaseena18@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/arshiya-tabassum-043831269/)

---

## 📜 License

This project is licensed under the MIT License.
