# 🌃 Automatic Street Light Controller | Energy-Efficient IoT System

An **energy-efficient Automatic Street Light Controller** designed using **ESP32 / Arduino**, **LDR sensor**, and a **relay module**.  
This project automates the process of turning street lights **ON at dusk** and **OFF at dawn**, optimizing energy consumption and reducing human intervention — a step toward **smart and sustainable city infrastructure**.

---

## 🔍 Overview

The system detects ambient light intensity using an **LDR (Light Dependent Resistor)** sensor.  
When the environment becomes dark, the controller activates the street light via a **relay module**.  
As light intensity increases (daytime), the system automatically turns the lights OFF.  
This ensures efficient energy usage, low maintenance, and autonomous operation.

---

## ⚙️ Features

- 🌞 **Automatic Light Sensing:** Detects real-time ambient light using LDR.  
- ⚡ **Smart Switching:** Automatically controls street lights via a relay.  
- 💡 **Microcontroller-Based:** Utilizes ESP32 or Arduino for decision making.  
- 🌱 **Energy-Efficient:** Minimizes electricity usage with intelligent switching.  
- 🧩 **Cost-Effective & Simple:** Easy to build, program, and deploy.

---

## 🧠 Technology Stack

| Category | Component / Tool |
|-----------|------------------|
| **Microcontroller** | ESP32 / Arduino UNO |
| **Sensor** | Light Dependent Resistor (LDR) |
| **Actuator** | Relay Module, LED Bulb |
| **Programming Language** | C / C++ |
| **IDE / Platform** | Arduino IDE |

---

## 🔧 Working Principle

1. The **LDR sensor** measures the surrounding light intensity.  
2. When the light level drops below a defined threshold (evening/night), the **relay module** turns **ON** the street light.  
3. When light intensity rises (morning/daylight), the **relay module** turns **OFF** the light.  
4. The **ESP32 / Arduino** processes sensor data in real time and controls the relay accordingly.  

This process runs continuously without any manual control.

---

## 🪛 Hardware Connections

| Component | Pin Connection (Arduino Example) |
|------------|----------------------------------|
| **LDR Sensor** | Analog Pin (A0) |
| **Relay Module** | Digital Pin (D3) |
| **LED / Street Light** | Connected via Relay Output |
| **Power Supply** | 5V / 3.3V (as per board) |



---

## 🖥️ Steps to Run the Project

1. Open **Arduino IDE**.  
2. Connect your **ESP32 / Arduino** board via USB.  
3. Load the provided sketch file.  
4. Select the correct **Board** and **COM Port**.  
5. Click **Upload** to flash the code.  
6. Power the setup and observe automatic ON/OFF switching based on light intensity.

---

## 🌍 Key Benefits

- ✅ Reduces power wastage by operating lights only when needed.  
- 🧠 Intelligent and fully automated operation.  
- 🔧 Low maintenance and high reliability.  
- 🏙️ Suitable for **Smart City** and **IoT-based** lighting systems.  
- 🌿 Promotes sustainable and green energy practices.

---

## 🪶 Future Enhancements

- 📶 Integration with IoT Dashboard for remote monitoring.  
- 📱 Mobile or web-based control interface.  
- ☁️ Cloud data storage and analytics for light usage patterns.  
- 🌡️ Addition of motion or temperature sensors for adaptive control.

---




