# Smart-Healing-System
Smart Healing system

🩺 Smart-Heal: Active Theranostic Wound Care System

Awarded/Showcased at Tamizhan Skills Ideathon 2026 🏆


📌 Project Overview

Smart-Heal is an IoT-enabled "Theranostic" (Therapy + Diagnostic) smart bandage designed to prevent diabetic amputations. Traditional wound dressings are passive—they only cover the wound. Smart-Heal actively defends it.

By continuously monitoring the wound's micro-climate and utilizing automated 405nm Blue Light Therapy, this system detects bacterial infections at their earliest stages and sterilizes the wound autonomously, eliminating the need for human intervention and preventing the spread of gangrene.


✨ Key Features

🌡️ Micro-Climate Monitoring: Real-time tracking of localized skin temperature and pH levels to detect early signs of inflammation and bacterial colonization.

💡 Automated Blue Light Therapy: Instantly activates 405nm sterilization light when infection parameters are met (e.g., Temp > 37.5°C or Alkaline pH).

📱 IoT Tele-Monitoring: Streams live wound data to doctors and caregivers via the Blynk IoT Cloud platform.

🚨 Smart Alerts: Visual onboard LED indicators (Safe/Critical) and push notifications for immediate medical attention.


🛠️ Hardware & Tech Stack

Microcontroller: ESP32-C3 SuperMini (Low power, compact footprint)

Sensors: NTC Thermistor (10kΩ), pH Sensor (Simulated via Potentiometer)

Actuators: Diffused Blue LED (405nm Therapy simulation), Red/Green status LEDs

Software: C++ (Arduino IDE), Blynk Simple ESP32, WiFi Multi


🧠 How It Works

Sense: The ultra-thin sensors rest near the wound bed, taking continuous readings.

Process: The ESP32-C3 evaluates the data against clinical thresholds for infection.

Act: If an infection is detected, the system overrides to "Critical Mode," illuminating the Red alert LED and bathing the wound in Blue sterilizing light.

Report: All data is logged to the cloud, allowing doctors to remotely trigger therapy or request a bandage change.
