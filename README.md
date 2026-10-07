# IoT and 5G – AAT Projects

![IoT](https://img.shields.io/badge/IoT-Projects-blue)
![Arduino](https://img.shields.io/badge/Arduino-UNO-00979D)
![ESP32](https://img.shields.io/badge/ESP32-Wokwi-red)
![STM32](https://img.shields.io/badge/STM32-Wokwi-blue)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-Pico-green)
![TinyML](https://img.shields.io/badge/TinyML-Embedded%20AI-orange)

A collection of Internet of Things (IoT), embedded systems, cloud monitoring, and TinyML simulations developed as part of the **Internet of Things and 5G** course.

---

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
 ┌─────────────────┐
 │ Dark → LED ON   │
 │ Light → LED OFF │
 └─────────────────┘
```

### Applications

- Smart city lighting
- Energy-efficient street lighting
- Automated lighting systems
- Sustainable infrastructure

### Simulation

[Tinkercad Simulation](https://www.tinkercad.com/things/kk75jx30q4E-remote-patient-monitoring?sharecode=Q4jgyYgvNHrJhOHfSG0MwzJSLlfgrCOR06lQy8_gOkU)

---

# 2. Smart Motion Detection System – ESP32 + ThingSpeak

### Description

A smart motion detection system developed using an **ESP32** and **PIR sensor**.

The PIR sensor detects human movement and the ESP32 processes the sensor data. An LED provides a visual indication and system status can be monitored through the Serial Monitor and ThingSpeak.

### Components

- ESP32
- PIR Sensor
- LED
- Resistor
- Wokwi
- ThingSpeak

### Working

```text
PIR Sensor
     ↓
ESP32
     ↓
Motion Detection
     ↓
 ┌────────────────────┐
 │ Motion Detected    │
 │        ↓           │
 │      LED ON        │
 └────────────────────┘
     ↓
ThingSpeak / Monitoring
```

### Applications

- Home security
- Office monitoring
- Restricted-area monitoring
- Automatic lighting
- Surveillance systems

### Simulation

[Wokwi ESP32 Project](https://wokwi.com/projects/460820904371564545)

---

# 3. Smart Irrigation System – STM32

### Description

A smart irrigation system designed using an **STM32 microcontroller** to automate irrigation according to soil moisture conditions.

A soil moisture sensor or potentiometer is used as the input. The system processes the moisture level and controls the irrigation output accordingly.

The system also demonstrates real-time feedback and alert mechanisms.

### Components

- STM32
- Soil Moisture Sensor / Potentiometer
- LCD
- LED / Pump
- Buzzer
- Wokwi

### Working

```text
Soil Moisture Sensor
        ↓
      STM32
        ↓
Read Moisture Level
        ↓
Compare Threshold
        ↓
 ┌──────────────────────┐
 │ Dry → Pump ON        │
 │ Normal/Wet → Pump OFF│
 └──────────────────────┘
        ↓
 LCD / Buzzer Feedback
```

### Applications

- Smart farming
- Automated irrigation
- Water conservation
- Agricultural automation

### Simulation

[Wokwi STM32 Project](https://wokwi.com/projects/460830329368907777)

---

# 4. Smart Theft Detection System – Raspberry Pi Pico

### Description

A low-cost smart security system developed using a **Raspberry Pi Pico** and motion sensing.

The system detects unauthorized movement and generates immediate alerts using an LED, buzzer, and display.

### Components

- Raspberry Pi Pico
- PIR / Motion Sensor
- LED
- Buzzer
- LCD
- Wokwi

### Working

```text
Motion Sensor
      ↓
Raspberry Pi Pico
      ↓
Check for Motion
      ↓
 ┌─────────────────────┐
 │ Motion Detected     │
 │        ↓            │
 │ LED + Buzzer ON     │
 │ Alert Display       │
 └─────────────────────┘
```

### Applications

- Home security
- Office security
- Warehouse monitoring
- Restricted-area protection
- Campus surveillance

### Simulation

[Wokwi Raspberry Pi Pico Project](https://wokwi.com/projects/460796653093014529)

---

# 5. TinyML-Based Crop Recommendation System

### Description

A **TinyML-based crop recommendation system** designed to assist farmers in selecting suitable crops based on soil and environmental parameters.

The project uses machine learning concepts and embedded processing to perform real-time prediction on an ESP32-based system.

The system demonstrates how **TinyML and IoT** can be combined for smart agriculture.

### Tools

- ESP32
- Wokwi
- Google Colab
- Python
- Machine Learning
- TinyML

### Input Parameters

The system considers parameters such as:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Humidity
- Temperature
- Soil and environmental conditions

### Working

```text
Soil & Environmental Parameters
              ↓
       Data Preprocessing
              ↓
      ML Model / TinyML Logic
              ↓
        ESP32 Processing
              ↓
        Crop Prediction
              ↓
         LED / Display
```

### Example Outputs

The embedded system demonstrates crop prediction using different output indicators, such as:

- Rice
- Maize
- Cotton

### Applications

- Smart agriculture
- Crop selection
- Precision farming
- Sustainable farming
- Data-driven agricultural decision making

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Arduino UNO | Embedded control |
| ESP32 | IoT and sensor processing |
| STM32 | Embedded automation |
| Raspberry Pi Pico | Security monitoring |
| Tinkercad | Arduino simulation |
| Wokwi | Embedded system simulation |
| ThingSpeak | IoT cloud monitoring |
| Google Colab | ML development |
| Python | Machine learning and data processing |
| TinyML | Machine learning on embedded devices |

---

# 🌱 Sustainable Development Goals

The projects are mapped to different UN Sustainable Development Goals:

- **SDG 2 – Zero Hunger**
- **SDG 7 – Affordable and Clean Energy**
- **SDG 9 – Industry, Innovation and Infrastructure**
- **SDG 11 – Sustainable Cities and Communities**
- **SDG 12 – Responsible Consumption and Production**
- **SDG 13 – Climate Action**
- **SDG 16 – Peace, Justice and Strong Institutions**

---

# 📂 Repository Structure

```text
IOT/
│
├── README.md
├── Report.pdf
├── link for iot projects.txt
│
└── Projects/
    ├── Arduino-Smart-Street-Light/
    ├── ESP32-Motion-Detection/
    ├── STM32-Smart-Irrigation/
    ├── Raspberry-Pi-Pico-Theft-Detection/
    └── TinyML-Crop-Recommendation/
```

> The project folders can be organized according to the corresponding source code, circuit diagrams, screenshots, and simulation links.

---

# 🎯 Learning Outcomes

Through these implementations, the project demonstrates:

- Basic IoT architecture
- Sensor and actuator integration
- Embedded programming
- Real-time sensor processing
- Microcontroller-based automation
- IoT cloud monitoring
- Wokwi-based embedded simulation
- Machine learning at the edge
- TinyML concepts
- Smart agriculture applications
- Smart city and security applications

---

# 📄 Documentation

The complete academic AAT report containing the five activities, circuit diagrams, source code, outputs, and project outcomes is included in:

```text
Report.pdf
```

---

# 👨‍💻 Author

**Devaraja Katti**

B.E. Artificial Intelligence & Machine Learning  
Dayananda Sagar College of Engineering, Bengaluru

---

⭐ If you find this repository useful, consider giving it a star!
