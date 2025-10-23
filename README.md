🌃 Automatic Street Light Controller (Energy Efficient)

Automatic Street Light Controller is an energy-efficient system designed to intelligently control street lighting based on ambient light levels. 💡 It automatically turns lights ON at dusk and OFF at dawn, helping save energy and reduce costs (up to 40% savings).

Key Features 🌟

💡 Automatic Light Control: Lights turn ON/OFF based on surrounding light conditions.

⚡ Energy Efficient: Reduces electricity consumption up to 40%.

🔌 Easy to Implement: Uses widely available components.

🛠️ Customizable: Can adjust sensor thresholds for different lighting conditions.

📱 Real-Time Monitoring: Observe light levels via serial monitor for debugging.

Components Used 🛠️

Arduino / ESP32

LDR (Light Dependent Resistor) Sensor

Relay Module

LED Bulbs

Resistors

How It Works 🔍

The LDR sensor continuously detects ambient light intensity.

When light falls below a certain threshold (dusk), the Arduino triggers the relay to turn ON the LED bulb.

When light exceeds the threshold (dawn), the relay switches the LED OFF.

Serial monitoring allows real-time observation of LDR readings for calibration.

Getting Started 🚀

Connect components as per the circuit diagram.

Upload the Arduino code to ESP32/Arduino board.

Open Serial Monitor to check LDR values.

Observe lights turning ON/OFF automatically based on ambient light.



