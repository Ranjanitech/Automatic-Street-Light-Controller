🌃 Automatic Street Light Controller | Energy-Efficient System

An Automatic Street Light Controller designed to save energy and operate smartly based on ambient light levels. This project is built using Arduino (ESP32) and is capable of reducing energy consumption by up to 40%.

🔹 Project Overview

The Automatic Street Light Controller system turns street lights ON at dusk and OFF at dawn automatically using a light-detecting sensor. It eliminates manual intervention and optimizes energy usage by only lighting areas when necessary.

This system is ideal for smart cities, residential areas, and public streets, helping reduce electricity costs and contributing to environmental sustainability.

🔹 Key Features

Automatic Light Control: Lights turn ON/OFF based on the surrounding brightness detected by the LDR sensor.

Energy-Efficient: Reduces electricity consumption by up to 40%.

Simple and Scalable: Easy to implement for multiple street lights using ESP32 and relays.

Real-Time Monitoring: Optional Serial Monitor display for light intensity readings for debugging.

🔹 Components Used
Component	Description
Arduino (ESP32)	Microcontroller to control sensors and relays
LDR Sensor	Detects ambient light levels
Relay Module	Switches street light ON/OFF
LED Bulb	Acts as the street light (or can be replaced by actual street lamps)
Resistors	Used to protect the LDR and control current
🔹 How It Works

The LDR sensor continuously measures the ambient light level.

The ESP32 reads the analog signal from the LDR.

If the light level falls below a certain threshold (e.g., at dusk), the relay is triggered, turning the LED light ON.

When the light level rises above the threshold (e.g., at dawn), the relay switches OFF the LED.

The system can be scaled to multiple street lights for larger implementations.

🔹 Circuit Diagram
LDR Sensor -> Analog Pin (ESP32)
Relay Module -> Digital Pin (ESP32)
LED Bulb -> Connected through Relay


The circuit ensures safe switching of high-power LED bulbs through the relay while reading ambient light via the LDR sensor.

🔹 Benefits

Reduces unnecessary electricity usage.

Increases the lifespan of street lights by avoiding continuous operation.

Cost-effective and easy to deploy.

Can be integrated with IoT for remote monitoring (optional future upgrade).

🔹 Future Enhancements

IoT integration to control and monitor street lights remotely.

Adding motion detection to switch lights ON only when movement is detected.

Solar-powered operation for sustainable street lighting.



