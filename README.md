# Weather Monitoring System with ThingSpeak  

## Overview  
This project is a **Weather Monitoring System** that uses an **ESP8266 NodeMCU** along with various sensors to collect real-time environmental data and upload it to **ThingSpeak** for visualization and analysis.  

## Features  
- Measures **temperature, humidity, atmospheric pressure, and rainfall**.  
- Uses **ThingSpeak** to display and analyze weather data.  
- Wi-Fi-enabled **ESP8266 NodeMCU** for wireless data transmission.  
- Provides real-time monitoring of environmental conditions.  

## Components Used  
- **NodeMCU ESP8266** (Wi-Fi module)  
- **DHT11** (Temperature and Humidity sensor)  
- **BMP180** (Barometric Pressure sensor)  
- **Rain Sensor**  
- **Breadboard & Jumper Wires**

## Circuit Diagram

   ![image](https://github.com/user-attachments/assets/d774f833-e391-4a39-9104-57972fecef47)


## Working Principle  
1. The sensors collect real-time weather data.  
2. The ESP8266 processes the data and sends it to ThingSpeak via Wi-Fi.  
3. ThingSpeak visualizes the data in graphical format.  
4. Users can monitor environmental conditions remotely.  

## Setup Instructions  
1. Connect the **DHT11, BMP180, and Rain Sensor** to **NodeMCU ESP8266**.  
2. Upload the **Arduino code** (`weather_monitoring_thingspeak.ino`) using the **Arduino IDE**.  
3. Configure **Wi-Fi credentials** and **ThingSpeak API Key** in the code.  
4. Monitor the weather data on your **ThingSpeak dashboard**.  

## How to Use  
- **Step 1:** Clone this repository  
  ```bash
  git clone https://github.com/your-username/weather-monitoring-system.git
- **Step 2:** Open weather_monitoring_thingspeak.ino in Arduino IDE.
- **Step 3:** Install required libraries (DHT, Adafruit BMP085, ESP8266WiFi, ThingSpeak).
- **Step 4:** Flash the code to ESP8266 NodeMCU.
- **Step 5:** Open ThingSpeak and view the live data.

