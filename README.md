# 🚰 Smart Gutter Management System

An IoT-based **Smart Gutter Management System** designed to monitor water levels, water flow, and potential drainage blockages using sensors and an ESP32 microcontroller.

The project focuses on improving drainage monitoring through **IoT, sensor-based data collection, automation, and AI/ML-based predictive analysis**, helping identify potential overflow and blockage conditions at an early stage.

---

## 🏆 Achievement

### Code Unnati Innovation Marathon 2024–25 — Semi-Finalist

The **Smart Gutter Management System** was selected as a **Semi-Finalist** in the **Code Unnati Innovation Marathon 2024–25**.

The project provided an opportunity to work on a real-world infrastructure problem using IoT and intelligent monitoring technologies.

**Achievement:** Semi-Finalist
**Event:** Code Unnati Innovation Marathon 2024–25
**Supported by:** SAP & Code Unnati

📜 The corresponding certificate is available in the folder.

---

## 📌 Project Overview

Traditional gutter and drainage systems can experience several problems, especially during heavy rainfall. Blockages caused by leaves, debris, and other materials can reduce water flow and result in overflow, stagnant water, flooding, and property damage.

The **Smart Gutter Management System** proposes an IoT-based approach for continuously monitoring drainage conditions.

The system uses sensors connected to an **ESP32** to collect information such as water level and water flow. The collected data can be processed and monitored to identify abnormal conditions and support timely maintenance.

The system can further be extended with cloud connectivity, alerts, and AI/ML-based predictive analysis.

---

## 🎯 Objectives

* Monitor water levels in real time.
* Measure water flow through the drainage system.
* Detect potential blockage conditions.
* Identify abnormal drainage conditions.
* Reduce dependency on manual gutter inspection.
* Provide real-time monitoring and alerts.
* Enable IoT-based remote monitoring.
* Explore AI/ML-based predictive maintenance.
* Improve drainage efficiency and reduce overflow risks.

---

## ⚙️ Key Features

### 🌊 Water Level Monitoring

The **HC-SR04 ultrasonic sensor** can be used to measure the distance between the sensor and the water surface, helping monitor changes in water level.

### 💧 Water Flow Monitoring

The **YF-S201 Hall Effect Water Flow Sensor** measures water flow by generating pulse signals corresponding to the movement of water.

### 🚨 Blockage Detection

Water-level and flow readings can be analyzed to identify unusual conditions that may indicate a potential blockage or restricted drainage.

### 📡 IoT Connectivity

The **ESP32** provides Wi-Fi connectivity for transmitting sensor data to an IoT or cloud-based monitoring platform.

### 📊 Data Monitoring

Sensor readings can be monitored and analyzed to understand drainage conditions and identify abnormal changes.

### 🤖 AI/ML-Based Analysis

Historical sensor data can be used with AI/ML techniques to analyze patterns and support predictive maintenance.

### 🔔 Alert System

The system can be configured to generate alerts when predefined water-level or flow thresholds are exceeded.

---

## 🛠️ Hardware Components

| Component                        | Purpose                                     |
| -------------------------------- | ------------------------------------------- |
| **ESP32**                        | Main microcontroller and Wi-Fi connectivity |
| **HC-SR04 Ultrasonic Sensor**    | Water-level measurement                     |
| **YF-S201 Water Flow Sensor**    | Water-flow measurement                      |
| **Ultrasonic / Blockage Sensor** | Blockage-condition monitoring               |
| **12V Rechargeable Battery**     | Power supply                                |
| **Jumper Wires**                 | Connecting electronic components            |
| **USB Cable**                    | Programming and power                       |

---

## 💻 Software & Technologies

* **MicroPython**
* **ESP32**
* **Python**
* **IoT**
* **MQTT**
* **AWS IoT**
* **AI/ML**
* **Data Analytics**
* **Web Dashboard**
* **Flutter / Android Studio**
* **Kotlin**
* **Database**

---

## 🔄 System Workflow

```text
              ┌─────────────────────┐
              │       Sensors       │
              │                     │
              │ Water Level Sensor  │
              │ Flow Rate Sensor    │
              │ Blockage Sensor     │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │        ESP32        │
              │ Data Collection &   │
              │ Processing          │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Wi-Fi / MQTT      │
              │ IoT Communication   │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Cloud Platform    │
              │    / Database       │
              └──────────┬──────────┘
                         │
                  ┌──────┴──────┐
                  ▼             ▼
          ┌─────────────┐ ┌─────────────┐
          │   Dashboard │ │   AI / ML   │
          │  Monitoring │ │   Analysis  │
          └──────┬──────┘ └──────┬──────┘
                 │               │
                 └───────┬───────┘
                         ▼
                ┌─────────────────┐
                │ Alerts &        │
                │ Maintenance     │
                └─────────────────┘
```

---

## 📐 Project Diagrams

### Block Diagram

<img width="976" height="849" alt="image" src="https://github.com/user-attachments/assets/212cb190-d53e-4ce2-8c72-f1b0cc580dc0" />


### Circuit Diagram

<img width="860" height="965" alt="image" src="https://github.com/user-attachments/assets/4fc2ef90-914e-4165-bd98-3527d827bc46" />


---

## 📸 Project Images

Project prototype, hardware setup, sensor connections, and output images are available in the [`images`](./images/) folder.

<img width="983" height="636" alt="image" src="https://github.com/user-attachments/assets/02c055e2-494d-49dd-afdc-515cf65351c0" />
<img width="983" height="625" alt="image" src="https://github.com/user-attachments/assets/979f77cd-6e16-4d29-950f-421b83f1a04a" />
<img width="983" height="591" alt="image" src="https://github.com/user-attachments/assets/1baddf35-a57a-460a-8bae-60f43080568f" />
<img width="983" height="638" alt="image" src="https://github.com/user-attachments/assets/e1230e6d-981e-44f2-9576-c67649180946" />
<img width="971" height="1252" alt="image" src="https://github.com/user-attachments/assets/2fb13c62-a858-43a9-8db0-1d3ed37844c2" />

---

## 🔬 Working Operation

### 1. Sensor Data Collection

The sensors collect real-time information about the water level and flow conditions inside the drainage system.

### 2. Data Processing

The ESP32 receives the sensor readings and processes them according to predefined conditions and threshold values.

### 3. IoT Communication

The processed data can be transmitted through Wi-Fi using communication protocols such as **MQTT**.

### 4. Monitoring

The collected information can be displayed through a monitoring interface or dashboard for easier observation of drainage conditions.

### 5. Abnormal Condition Detection

If the water level rises significantly or the water flow decreases unexpectedly, the system can identify the condition as a possible overflow or blockage situation.

### 6. Alerts

The system can generate notifications when critical threshold conditions are detected, allowing users to take timely action.

### 7. Predictive Analysis

Historical sensor data can be analyzed using AI/ML techniques to identify patterns and support predictive maintenance.

---

## 🏆 Competition & Recognition

### Code Unnati Innovation Marathon 2024–25

**Result: Semi-Finalist**

The project was selected as a **Semi-Finalist** in the Code Unnati Innovation Marathon 2024–25.

The competition provided practical exposure to:

* IoT-based problem solving
* Sensor integration
* Prototype development
* Real-world problem identification
* Technical presentation
* Innovation and solution development
* Team collaboration

📜 **Certificate:** <img width="990" height="703" alt="image" src="https://github.com/user-attachments/assets/a5f9a5f9-078f-41d7-a7cc-19e8aadd5169" />


---


## 👩‍💻 Team Members

### Priya Gupta Gangaram

Project Team Member

### Nikki Ram Subodh

Project Team Member

### Project Guide

**Mr. Pawan Singh**

---

## 🔮 Future Scope

The Smart Gutter Management System can be further enhanced with the following features:

### 🤖 AI-Based Predictive Analytics

Advanced machine learning or deep learning models can analyze historical sensor readings, weather conditions, and drainage patterns to predict potential blockages or overflow conditions.

### 🏙️ Smart City Integration

The system can be integrated with municipal drainage networks and smart-city infrastructure for large-scale monitoring and management.

### ☀️ Solar-Powered Units

Solar panels and energy-efficient components can be integrated to support continuous operation and reduce dependency on external power sources.

### 🌧️ Weather-Based Automation

Weather forecast data can be integrated to prepare the drainage system for heavy rainfall and generate early warnings.

### 🧹 Automated Debris Removal

Future versions can include automated cleaning mechanisms such as robotic cleaning arms or water jets for removing accumulated debris.

### 📱 Mobile Application

A dedicated mobile application can allow users to monitor water levels, flow rates, alerts, and system status remotely.

### 💬 AI Chatbot & Voice Control

AI-powered chatbot and voice-control features can provide users with a more interactive way to monitor and control the system.

---

## 🌱 Potential Benefits

The proposed system can help to:

* Improve drainage monitoring.
* Reduce manual inspection.
* Detect abnormal water conditions.
* Identify potential blockage conditions.
* Reduce the risk of water overflow.
* Support proactive maintenance.
* Enable remote monitoring.
* Improve drainage management.
* Support smart-city infrastructure development.

---

## 📊 Project Domain

| Category            | Details                                               |
| ------------------- | ----------------------------------------------------- |
| **Project Type**    | Academic / Innovation Project                         |
| **Domain**          | IoT + AI/ML + Smart Infrastructure                    |
| **Microcontroller** | ESP32                                                 |
| **Programming**     | MicroPython / Python                                  |
| **Communication**   | Wi-Fi / MQTT                                          |
| **Sensors**         | HC-SR04, YF-S201                                      |
| **Cloud**           | AWS IoT                                               |
| **Achievement**     | Code Unnati Innovation Marathon 2024–25 Semi-Finalist |

---

## 📁 Repository Structure

```text
smart-gutter-management-system/
│
├── README.md
│
├── src/
│   └── smart_gutter_code.py
│
├── hardware/
│   ├── block-diagram.png
│   ├── circuit-diagram.png
│   └── pcb-layout.png
│
├── images/
│   ├── project-setup.png
│   ├── sensor-setup.png
│   └── output-dashboard.png
│
├── certificates/
│   ├── code-unnati-semi-finalist-certificate.pdf
│   └── other-certificates.pdf
│
└── requirements.txt
```

---

## 📚 References

1. Smart Drainage Monitoring and Controlling System Using IoT
2. Smart Real-Time Drainage Monitoring System
3. Research papers related to IoT-based drainage monitoring
4. Roboflow datasets related to drain detection
5. Additional research resources used during project development

---

## ⭐ Project Status

**Status:** Academic / Innovation Project
**Achievement:** Code Unnati Innovation Marathon 2024–25 — Semi-Finalist
**Domain:** IoT + AI/ML + Smart Infrastructure
**Platform:** ESP32

---



