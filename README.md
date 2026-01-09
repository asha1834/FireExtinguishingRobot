# 🔥 IoT Enabled Fire Extinguishing Robot

An autonomous, sensor-driven firefighting robot built using **ESP32**, designed to detect fire, navigate around obstacles, suppress flames, and send **real-time alerts with GPS location** via the **Blynk IoT platform**. This project focuses on safety automation, remote monitoring, and intelligent navigation in hazardous environments.

---

## 🚀 Features

* 🔥 **Automatic Fire Detection** using flame sensors
* 🧭 **Autonomous Navigation** with ultrasonic obstacle avoidance
* 💦 **Fire Suppression System** controlled via relay
* 📍 **Live GPS Tracking** for fire location
* 📲 **Real-Time Alerts & Monitoring** using Blynk IoT
* ⚡ **Low-Power Embedded Design** for extended operation

---

## 🛠 Tech Stack

**Hardware:**

* ESP32 Microcontroller
* Flame Sensor
* Ultrasonic Sensor (HC-SR04)
* GPS Module
* DC Motors + Motor Driver
* Relay Module
* Water Pump / Fire Suppression Unit

**Software:**

* Embedded C / Arduino Framework
* Blynk IoT Platform
* Wi-Fi Communication

---

## ⚙️ System Workflow

1. Robot continuously monitors for fire using a flame sensor.
2. On detection, motors stop and the suppression system is activated.
3. GPS coordinates are fetched in real time.
4. Location and fire alert are sent to the Blynk mobile app.
5. If no fire is detected, the robot navigates autonomously while avoiding obstacles.

---

## 📐 Architecture Overview

* **ESP32** acts as the central controller
* **Flame Sensor** triggers detection
* **Ultrasonic Sensor** ensures obstacle avoidance
* **Relay Module** controls the water pump
* **GPS Module** provides location data
* **Blynk IoT** displays alerts and status remotely

---

## 🔧 Pin Configuration

| Component       | Pin     |
| --------------- | ------- |
| Flame Sensor    | 18      |
| Ultrasonic TRIG | 23      |
| Ultrasonic ECHO | 22      |
| Relay Module    | 33      |
| Motor A1        | 13      |
| Motor A2        | 12      |
| Motor B1        | 14      |
| Motor B2        | 27      |
| GPS RX / TX     | 16 / 17 |

---

## 📲 Blynk Integration

* **V4:** Latitude
* **V5:** Longitude
* **V6:** Fire Status LED
* **Event:** `fire_alert` triggered on detection

Make sure to configure your Blynk template and authentication token in the code.

---

## ▶️ How to Run

1. Clone the repository.
2. Open the project in Arduino IDE.
3. Install required libraries:

   * `Blynk`
   * `TinyGPSPlus`
4. Update Wi-Fi credentials and Blynk Auth Token.
5. Upload code to ESP32.
6. Power the robot and monitor via the Blynk mobile app.

---

## 🧪 Testing

* Test flame detection using a safe heat/light source.
* Validate obstacle detection with nearby objects.
* Confirm GPS location is updating in Blynk.
* Ensure relay activates the pump during fire detection.

---

## 🌍 Applications

* Residential Fire Safety
* Warehouses & Industrial Plants
* Offices & Server Rooms
* Educational Robotics Projects

---

## 🔮 Future Enhancements

* 🤖 AI-based fire detection using camera vision
* ☁️ Cloud dashboard for analytics & history
* 🧯 CO₂-based suppression for electrical fires
* 🗺 Smart path optimization algorithms

---

## 👩‍💻 Author

**Asha**
Full Stack Developer | IoT & Embedded Systems Enthusiast

---

## ⭐ Show Your Support

If you found this project helpful or inspiring, give it a ⭐ on GitHub and share it with fellow developers!
