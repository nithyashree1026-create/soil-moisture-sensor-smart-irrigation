# 🌱 Soil Moisture Sensor – Smart Irrigation Systems
## 📌 Overview
Soil moisture sensors are used to measure the water content present in soil. These sensors play an important role in smart agriculture, automated irrigation systems, and environmental monitoring applications.
This repository explores the sensing principle, electrical behavior, ESP32 interfacing, and IoT integration of soil moisture sensors.
## 🧠 Working Principle
Most soil moisture sensors operate based on electrical conductivity.
Wet soil conducts electricity better than dry soil due to the presence of water and dissolved minerals.
### 🔹 Sensor Behavior:
* Wet soil → Lower resistance
* Dry soil → Higher resistance
The sensor converts this variation into voltage changes that can be processed by ESP32.
## ⚙️ Sensor Structure
A typical soil moisture sensor contains:
* Conductive probe electrodes
* Signal conditioning module
* Analog and digital outputs
The probes are inserted into soil to measure conductivity levels.
## 🔌 Output Characteristics
### 🔹 Analog Output:
Provides continuous moisture values.
### 🔹 Digital Output:
Uses threshold comparison for ON/OFF detection.
## 📡 ESP32 Interfacing
ESP32 reads analog moisture values using ADC pins.
### 🔹 Working Flow:
* Sensor measures soil conductivity
* Voltage level changes
* ESP32 reads ADC value
* Irrigation logic is executed
## 🌐 IoT Integration
