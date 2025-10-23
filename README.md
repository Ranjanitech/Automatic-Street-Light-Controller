# 🌃 Automatic Street Light Controller (Energy Efficient)

This project is an **energy-efficient Automatic Street Light Controller** designed using **ESP32 / Arduino**, **LDR sensor**, **relay module**, and **LED bulbs**.  
It intelligently turns street lights **ON at dusk** and **OFF at dawn** by detecting ambient light levels — saving energy, reducing manual effort, and supporting sustainable energy usage.

---

## 🚀 Features

- 🌞 **Automatic Light Detection** — Uses an LDR sensor to detect ambient light intensity.  
- ⚡ **Smart Control** — Automatically turns lights ON/OFF via a relay module.  
- 💡 **Microcontroller-Based** — Built using ESP32 or Arduino for real-time decision-making.  
- 🌱 **Energy Efficient** — Operates only when necessary to reduce electricity waste.  
- 🧩 **Simple & Cost-Effective** — Minimal components, easy to build and maintain.

---

## 🧠 Technology Stack

| Component Type | Description |
|----------------|--------------|
| **Microcontroller** | ESP32 / Arduino |
| **Sensor** | Light Dependent Resistor (LDR) |
| **Actuator** | Relay Module, LED Bulbs |
| **Programming Language** | C / C++ (Arduino IDE) |

---

## ⚙️ How It Works

1. The **LDR sensor** continuously measures ambient light intensity.  
2. When the light level **drops below a threshold** (evening/night), the **relay** activates and turns **ON** the street light.  
3. When the light level **rises again** (morning/daylight), the relay switches the light **OFF**.  
4. This process occurs **automatically and continuously** without any human intervention.

---

## 🔌 Circuit Setup

1. Connect **LDR sensor** to the analog input of the microcontroller.  
2. Connect **relay module** to a digital output pin.  
3. Attach **LED bulb** (or load) to the relay output.  
4. Upload the **Arduino sketch** to the ESP32/Arduino board.  
5. Power up the system and observe the **automatic switching** of street lights.

---

## 💼 Usage

1. Open **Arduino IDE** and load the project code.  
2. Select the appropriate **board (ESP32 / Arduino)** and **COM port**.  
3. Upload the code to your microcontroller.  
4. Observe lights turning ON/OFF automatically according to ambient light levels.

---

## 🌍 Benefits

- ⚡ **Energy Saving** – Lights operate only when required.  
- 🧠 **Smart Automation** – Fully automatic operation with no manual control needed.  
- 🔧 **Low Maintenance** – Minimal hardware components ensure easy upkeep.  
- 🏙️ **Smart City Ready** – Ideal for modern urban lighting systems.

---




