# Smart Traffic Light Control System (ATmega32)

A robust and intelligent traffic light management system developed using the **ATmega32** microcontroller. This project simulates a real-world traffic junction with precise timing logic and environmental monitoring features.

## 🚦 Project Overview
This system controls a standard 3-color traffic light (Red, Green, Yellow) with a dynamic countdown display. Additionally, it integrates environmental sensors to provide real-time data to drivers, enhancing road safety and awareness.

## ✨ Key Features
* **Precise Timing Logic:** * **Red Light:** Counts down from **40 to 4** seconds.
    * **Green Light:** Counts down from **37 to 1** seconds.
    * **Yellow Light:** Counts down from **3 to 1** seconds.
* **Environmental Monitoring:** Integrated **DHT11** sensor to measure and display temperature and humidity on an LCD.
* **Driver Information System:** Displays safety messages and environmental data to the driver during the wait time.
* **Hardware Simulation:** Fully tested and verified using **Proteus** schematics.

## 🛠️ Hardware Components
* **Microcontroller:** ATmega32 (AVR Architecture).
* **Display:** 16x2 Character LCD.
* **Sensor:** DHT11 (Temperature & Humidity).
* **Indicators:** High-brightness LEDs (Red, Green, Yellow).
* **Peripheral ICs:** PCF8574 (for I2C LCD interfacing, if used) or direct GPIO connection.

## 💻 Tech Stack
* **Programming Language:** C.
* **Development Environment:** Atmel Studio 7.0 / Microchip Studio.
* **Simulation:** Proteus 8.

## 🔌 Circuit Design
*(You can upload your Proteus screenshot to your repo and link it here)*
![Traffic Light Schematic](Project_Files/Traffic_Light_Schematic.png)

## 📖 How to Run
1.  Open the `.pdsprj` file in **Proteus**.
2.  Load the compiled `.hex` file (found in the Debug folder) onto the ATmega32 chip.
3.  Run the simulation to observe the countdown sequence and sensor readings on the LCD.