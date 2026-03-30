# 🗑️ Smart Garbage Bin Monitoring System (IoT)

A smart, touch-free garbage bin using Arduino, ultrasonic sensor, and servo motor to improve hygiene and support smart city solutions.

---

## Overview
The Smart Garbage Bin Monitoring System is an IoT-based project designed to improve hygiene and efficiency in waste management. The system automatically opens the bin lid when a user approaches, reducing the need for physical contact.

This project demonstrates how simple hardware components can be used to create smart, real-world solutions aligned with modern smart city concepts.

---

## Objectives
- Design and build a smart garbage bin using Arduino  
- Detect user presence using an ultrasonic sensor  
- Automatically open and close the lid using a servo motor  
- Create a foundation for future IoT-based smart waste systems  

---

## Features
- Touch-free operation  
- Automatic lid opening and closing  
- Real-time distance detection  
- Simple and cost-effective design  
- Expandable for IoT and smart city applications  

---

## How It Works
1. The ultrasonic sensor continuously measures the distance to nearby objects  
2. When an object is detected within a predefined range (e.g., 20 cm), the system:
   - Sends a signal to the servo motor  
   - Opens the lid automatically  
3. When the object moves away:
   - The lid closes automatically  

---

## Components Used
- Arduino UNO (Microcontroller)  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (SG90)  

---

##  Software & Tools
- Arduino IDE (for coding and uploading the program)  
- Tinkercad (for circuit simulation and testing)  

---

##  Pin Connections
| Component | Pin | Arduino Connection |
|----------|-----|-------------------|
| Ultrasonic Sensor | VCC | 3.3V |
| Ultrasonic Sensor | GND | GND |
| Ultrasonic Sensor | TRIG | D10 |
| Ultrasonic Sensor | ECHO | D11 |
| Servo Motor | VCC | 5V |
| Servo Motor | GND | GND |
| Servo Motor | Signal | D9 |

---


---

## Data Collected
- Distance (cm) measured by the ultrasonic sensor  
- Lid status (open/closed) based on user presence  

---

## Significance
This project contributes to:
- Improved public hygiene  
- Reduced human contact with waste  
- Smarter waste management systems  

It also aligns with **smart city initiatives** and sustainable development goals.

---




