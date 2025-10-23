Automatic Street Light Controller
This project is an energy-efficient automatic street light controller that can save up to 40% of energy. Designed to turn street lights ON at dusk and OFF at dawn automatically, it ensures optimal power usage and extends the lifespan of street lighting.

Components
Arduino ESP32: The microcontroller that controls the overall operation.

LDR Sensor: Detects ambient light intensity to determine whether it is day or night.

Relay Module: Acts as a switch to turn the LED bulb ON or OFF based on control signals from the Arduino.

LED Bulb: The street light or lamp that is controlled.

Resistors: Used for current regulation and sensor circuit stability.

Working Principle
The LDR (Light Dependent Resistor) sensor senses the surrounding light levels. When ambient light falls below a defined threshold (indicating nightfall), the Arduino triggers the relay module to turn ON the LED bulb. Conversely, when light levels rise above the threshold (daytime), the relay switches OFF the LED bulb. This automation enhances energy efficiency by ensuring the street light is only ON during low-light conditions.

Key Benefits
Up to 40% energy savings by reducing unnecessary power usage.

Prolongs the lifespan of street lights by reducing manual ON/OFF switching.

Simple, cost-effective, and reliable solution suitable for smart lighting applications in streets and public areas.

How to Use
Connect the LDR sensor, relay module, LED bulb, and resistors to the ESP32 board as per the circuit design.

Upload the Arduino program which reads the LDR sensor values and controls the relay.

Adjust the threshold light level in the code to calibrate when the lights should turn ON/OFF.

Power the system, and it will automatically control street lighting based on ambient light.

This project embodies efficient resource utilization and smart automation using readily available electronics components.



