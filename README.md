# IoT and 5G – AAT Projects

![IoT](https://img.shields.io/badge/IoT-Projects-blue)
![Arduino](https://img.shields.io/badge/Arduino-UNO-00979D)
![ESP32](https://img.shields.io/badge/ESP32-Wokwi-red)
![STM32](https://img.shields.io/badge/STM32-Wokwi-blue)
![Raspberry%20Pi](https://img.shields.io/badge/Raspberry%20Pi-Pico-green)
![TinyML](https://img.shields.io/badge/TinyML-Embedded%20AI-orange)

A collection of Internet of Things (IoT), embedded systems, cloud monitoring, and TinyML simulations developed as part of the **Internet of Things and 5G** course.

## 🎓 Academic Information

- **College:** Dayananda Sagar College of Engineering, Bengaluru
- **Department:** Artificial Intelligence & Machine Learning
- **Course:** Internet of Things and 5G
- **Course Code:** 22AI642
- **Semester:** VI
- **Academic Year:** 2025–26
- **Student:** Devaraja Katti
- **USN:** 1DS23AI020
- **Course Coordinator:** Dr. Aruna M G

---

# 📌 Projects

## 1. Smart Street Lighting System – Arduino UNO

### Description

An IoT-based smart street lighting system that automatically controls a street light according to ambient light intensity.

An **LDR sensor** is connected to an Arduino UNO to detect surrounding light conditions. The LED is automatically turned ON during low-light conditions and OFF during high-light conditions.

### Components

- Arduino UNO
- LDR Sensor
- LED
- Resistor
- Tinkercad

### Working

```text
LDR Sensor
     ↓
Arduino UNO
     ↓
Read Light Intensity
     ↓
Compare with Threshold
     ↓
 ┌───────────────┐
 │ Dark → LED ON │
 │ Light → LED OFF
 └───────────────┘
