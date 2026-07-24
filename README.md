# Smart Environment Monitor using ESP32

A real-time **IoT-based Smart Environment Monitoring System** developed using the **ESP32 microcontroller**, **DHT22 temperature and humidity sensor**, and a **16×2 I2C LCD display**. The system continuously monitors environmental conditions by reading temperature and humidity values every 2 seconds, displaying the data on the LCD while simultaneously sending it to the Serial Monitor for real-time monitoring and debugging.

---

## Project Overview

The **Smart Environment Monitor** demonstrates the fundamentals of embedded systems and IoT development. It interfaces a DHT22 digital sensor with an ESP32 microcontroller to measure environmental temperature and humidity. The collected sensor data is displayed on an I2C LCD and printed to the Serial Monitor, providing an efficient way to monitor ambient conditions in real time.

This project highlights essential concepts such as GPIO configuration, digital sensor interfacing, I2C communication, and serial communication.

---

## Project Objectives

- Interface a DHT22 sensor with the ESP32 microcontroller.
- Measure ambient temperature and humidity every 2 seconds.
- Display sensor readings on a 16×2 I2C LCD.
- Print environmental data to the Serial Monitor.
- Demonstrate fundamental embedded systems and IoT concepts.

---

## Features

-  Real-time temperature monitoring
-  Real-time humidity monitoring
-  Live display on a 16×2 I2C LCD
-  Serial Monitor output for debugging
-  Automatic sensor updates every 2 seconds
-  ESP32-based embedded application
-  Simulated and tested using Wokwi

---

## Hardware Components

| Component | Quantity |
|-----------|---------:|
| ESP32 Development Board | 1 |
| DHT22 Temperature & Humidity Sensor | 1 |
| 16×2 I2C LCD Display | 1 |
| Jumper Wires | As Required |

---

## Software Requirements

- Arduino IDE
- ESP32 Board Package
- DHT Sensor Library
- LiquidCrystal_I2C Library
- Wokwi Simulator
- Arduino (C++)

---

## Pin Connections

### LCD (I2C)

| LCD (I2C) | ESP32 |
|------------|-------|
| **GND** | GND |
| **VCC** | 5V |
| **SDA** | GPIO 21 |
| **SCL** | GPIO 22 |

### DHT22 Sensor

| DHT22 | ESP32 |
|--------|-------|
| **VCC** | 3.3V |
| **GND** | GND |
| **DATA** | GPIO 4 |

---

## How It Works

1. The ESP32 initializes the DHT22 sensor and the I2C LCD display.
2. Every 2 seconds, the ESP32 reads temperature and humidity values from the DHT22 sensor.
3. The acquired sensor data is processed by the ESP32.
4. The temperature and humidity readings are displayed on the 16×2 I2C LCD.
5. The same readings are transmitted to the Serial Monitor for monitoring and debugging.
6. This process repeats continuously, providing real-time environmental monitoring.

---

## Test Results

| Test Case | Temperature (°C) | Humidity (%) | LCD Display Output | Serial Monitor Output |
| ---------- | ---------------: | -----------: | ------------------ | --------------------- |
| **Test Case 1** | **24.00°C** | **40.00%** | `Temp:24.00°C`<br>`Hum:40.00%` | `Temperature: 24.00 C    Humidity: 40.00 %` |
| **Test Case 2** | **27.50°C** | **55.00%** | `Temp:27.50°C`<br>`Hum:55.00%` | `Temperature: 27.50 C    Humidity: 55.00 %` |
| **Test Case 3** | **31.20°C** | **68.00%** | `Temp:31.20°C`<br>`Hum:68.00%` | `Temperature: 31.20 C    Humidity: 68.00 %` |

---

## Sample Output

### Test Case 1

- **Temperature:** 24.00°C
- **Humidity:** 40.00%
- **Status:** Normal indoor conditions.

### Test Case 2

- **Temperature:** 27.50°C
- **Humidity:** 55.00%
- **Status:** Warm with moderate humidity.

### Test Case 3

- **Temperature:** 31.20°C
- **Humidity:** 68.00%
- **Status:** Hot and humid environment.

---

## Built With

- **ESP32** – Microcontroller
- **Arduino IDE**
- **Arduino (C++)**
- **DHT22 Temperature & Humidity Sensor**
- **16×2 I2C LCD**
- **DHT Sensor Library**
- **LiquidCrystal_I2C Library**
- **Wokwi Simulator**

---



## Author

**Tarun Senthil**

**ESP32 • IoT • Embedded Systems • Arduino • DHT22 • Wokwi**
