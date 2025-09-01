# Solar-powered-weather-monitoring-system
🌦️ Solar Powered Weather Monitoring System

A low-power IoT-based weather monitoring system powered by solar energy. The system monitors temperature, humidity, light intensity, and atmospheric pressure using embedded sensors. Data is transmitted via ESP32 Wi-Fi module for real-time monitoring. Designed for continuous operation using solar panel + battery for energy harvesting.

🚀 Features

Solar-powered and designed for continuous operation.

Monitors:

🌡️ Temperature & Humidity (DHT11 Sensor)

💡 Light Intensity (LDR Sensor)

🌍 Atmospheric Pressure (BMP180 Sensor)

Low-power embedded design using Arduino Uno.

Wi-Fi enabled remote monitoring via ESP32.

Real-time data logging for analysis.

🛠️ Tech Stack

Microcontrollers: Arduino Uno, ESP32 Wi-Fi Module

Programming Language: Embedded C (Arduino IDE)

Components:

DHT11 Sensor (Temperature & Humidity)

LDR (Light Intensity)

BMP180 (Pressure)

Solar Panel

Battery & Charge Controller

Breadboard, Power Supply

⚡ Circuit Diagram (Connections)
Component	Arduino Pin
DHT11 Data	2
LDR	A0
BMP180 (I2C)	A4 (SDA), A5 (SCL)
ESP32 TX	Arduino RX (Pin 0)
ESP32 RX	Arduino TX (Pin 1)
Power Source	Solar Panel + Battery

(Adjust pins if you wired differently)

📜 Code

The repository contains two main codes:

Arduino Uno Code → Reads sensors and sends data to ESP32.

ESP32 Code → Connects to Wi-Fi and hosts a web server for live monitoring.

👉 Check the Arduino Code
 and ESP32 Code
.

🔧 How It Works

The Arduino Uno reads sensor data (temperature, humidity, pressure, light intensity).

Data is sent to the ESP32 over UART.

The ESP32 connects to Wi-Fi and hosts a web dashboard.

A solar panel + battery + charge controller ensures 24/7 power.



🚦 Future Improvements

Add cloud integration (ThingSpeak, Firebase, Google Sheets) for remote access.

Use low-power sleep modes to increase battery life.

Add OLED/TFT display for local monitoring.

Extend with rain sensor / wind sensor.

📌 Author
👩‍💻 Yuktha Dodda Rangappa
🔗 https://github.com/YukthaDoddaRangappa










