# 🌱 Smart Greenhouse Automation System

## Overview

This project simulates a Smart Greenhouse using Arduino in Tinkercad. It monitors temperature, humidity, and light conditions, then controls actuators to maintain optimal conditions. The system also supports data transmission via Bluetooth and GSM simulation for remote monitoring.

---

## Features

* **Temperature Sensor (TMP36)** – Reads real-time temperature.
* **Humidity (Simulated)** – Randomized values for greenhouse moisture.
* **LDR Sensor** – Detects Day/Night and adjusts irrigation thresholds.
* **Actuators:**

  * Water Pump (LED/Motor) – Turns ON when humidity is low.
  * Alert LEDs – Green (humidity), Red (temperature).
* **Wireless Communication:**

  * **Bluetooth** – Sends data to Arduino 2.
  * **GSM Simulation** – Sends data to Arduino 3.
* **LCD Display** – Shows humidity, temperature, and mode (Day/Night).

---

## Components

* Arduino Uno (x3)
* LCD (16x2)
* TMP36 Temperature Sensor
* LDR (Light Sensor) + 10kΩ Resistor
* LEDs (Red, Green)
* DC Motor or LED for Pump
* Bluetooth Module (simulated with SoftwareSerial)
* GSM Module (simulated)
* Breadboard, wires, resistors

---

## How It Works

* Reads **temperature**, simulates **humidity**, and checks **light level**.
* Adjusts irrigation based on **Day/Night mode**:

  * Day → Normal thresholds (Humidity < 40%)
  * Night → Lower thresholds (Humidity < 30%)
* Displays data on LCD and transmits via **Bluetooth & GSM**.

---

## Simulation

This project was built and tested on **Tinkercad**.
👉 [Tinkercad Project Link](https://www.tinkercad.com/things/k1AClviADXL-project/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fclassrooms%2Fhn5fE84EiK5%2Factivities%2FhHcAkQhkEdf%3Ftype%3Dcircuits)

---

## Unique Feature

* **Day/Night Mode** using LDR for energy and water-saving automation.

---

### Author

Nyakio E. Ndambiri – *Smart Farming Automation Project*

Copy and tinker this and email me for any additions 

EMAIL: ndambirinyakio@gmail.com & esther.ndambiri@strathmore.edu

---


