# 💊 Smart MediBox

![Platform](https://img.shields.io/badge/platform-ESP32-blue?logo=espressif)
![Sensors](https://img.shields.io/badge/sensors-DHT11%2C%20RTC%2C%20Touch-green)
![Communication](https://img.shields.io/badge/Connectivity-WiFi%20%7C%20Bluetooth-purple?logo=bluetooth)
![UI](https://img.shields.io/badge/UI-OLED%20%7C%20LEDs%20%7C%20Buttons-orange)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)

---

A **smart medication reminder device** designed to ensure timely medicine intake with **visual, sound, and IoT-enabled notifications**.
Powered by **ESP32** with integrated sensors and external feedback systems.

---

## 📖 Overview

The **Smart MediBox** is an IoT-enabled system that assists patients and caregivers by:

* ⏰ **Reminding users to take medication on time** using alarms and notifications
* 🌡️ **Monitoring temperature and humidity** to ensure medicine is stored in safe conditions
* 📟 **Providing real-time interaction** through an OLED display, LEDs, and sound alerts
* 📲 **Supporting wireless connectivity** with Wi-Fi and Bluetooth

---

## 🛠️ Tech Stack

### 🔧 Inputs

* Push buttons for MediBox setting configuration
* **DHT11** sensor for temperature & humidity monitoring
* ESP32 built-in sensors:

  * 🕒 **RTC (Real Time Clock)**
  * 👆 **Touch sensor**
  * 🧲 **Hall effect sensor**

### 💡 Outputs

* 🔊 **Buzzer** for sound feedback
* 📟 **OLED display** for user interface
* 💡 **LED bulbs** for visual feedback

### ☁️ Communication

* 🌐 **Wi-Fi**
* 📶 **Bluetooth**

---

## 🚀 Features

* ⚙️ **Programmable user interface** for medication schedules
* ⏰ **Rings alarm & notifies user** when it’s time to take medicine
* 🌡️ **Environmental monitoring** – alerts if temperature/humidity exceed safe ranges
* 📟 **Real-time visual + audio feedback**

---

## 📂 Repository Structure

```bash
├── hardware/        # PCB design or circuit schematics  
├── firmware/        # ESP32 code (PlatformIO / Arduino IDE)  
├── enclosure/       # 3D models/design files for MediBox case  
├── docs/            # Documentation and images  
└── README.md        # Project overview  
```

---

## 📸 Project Preview

(Add photos of your MediBox prototype, OLED UI, and sensor readings here)

---

## ✅ Result

A **functional IoT-based Smart MediBox** that ensures:

* Patients take their medication **on time**
* Medicines are stored under **safe environmental conditions**
* Caregivers can rely on **visual, sound, and IoT notifications**

---

## 📌 Future Improvements

* 📱 Integration with **mobile app** for remote notifications
* 📊 Cloud-based **data logging** for medicine intake tracking
* 🔋 Battery-powered version for portability
* 🧠 AI-based scheduling & smart reminders
  
---

## 📜 License

This project is licensed under the **MIT License** – open for use and modification.

---

