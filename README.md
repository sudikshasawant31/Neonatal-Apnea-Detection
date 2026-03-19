# 🧠 OS Insurgents

## 👶 Contactless Neonatal Breathing & Apnea Detection System

---

## 📌 Overview

Neonatal apnea is a critical condition where newborns suddenly stop breathing without warning. Continuous monitoring is essential, but existing systems are often invasive, expensive, and uncomfortable for infants.

This project presents a **contactless, real-time monitoring system** using **ESP32-CAM and computer vision** to detect infant breathing patterns and identify apnea events instantly. The system ensures **early detection, immediate alerts, and improved neonatal safety**.

---

## 🚨 Problem Statement

* Newborns can stop breathing silently without visible signs
* Existing systems use **contact-based sensors** (wires, electrodes)
* Risk of **infection, discomfort, and false alarms**
* Continuous manual monitoring is **not practical**
* High cost limits accessibility in rural and low-resource settings

---

## 💡 Proposed Solution

We developed a **non-invasive, camera-based monitoring system** that:

* Detects **chest movement using computer vision**
* Calculates **breathing rate in real time**
* Identifies **apnea events instantly**
* Triggers **alerts via buzzer, LED, and OLED display**

---

## ⚙️ Key Features

✅ Contactless monitoring (no sensors attached to baby)
✅ Real-time breathing detection
✅ Instant apnea alert system
✅ Low-cost and scalable solution
✅ OLED display for live status
✅ Suitable for NICU, home care, and rural healthcare

---

## 🧩 System Architecture

1. **ESP32-CAM** captures live video of infant
2. Video frames are processed using **OpenCV**
3. Chest motion is analyzed for breathing patterns
4. If no movement is detected for a threshold duration → **Apnea detected**
5. Alert triggered via:

   * 🔊 Buzzer
   * 💡 LED
   * 📺 OLED Display

---

## 🔧 Hardware Components

* ESP32-CAM
* ESP32 Microcontroller
* OLED Display
* Buzzer
* LEDs
* Power Supply

---

## 💻 Software & Tools

* Python
* OpenCV
* Embedded C (ESP32)
* Arduino IDE / PlatformIO

---

## 🔄 Working Principle

* Continuous video stream is captured
* Region of interest (chest area) is tracked
* Motion signal is extracted and analyzed
* Breathing pattern is calculated
* If breathing stops beyond threshold → alert is triggered

---

## 🌍 Applications

* NICU (Neonatal Intensive Care Units)
* Home monitoring for premature babies
* Rural healthcare centers
* Telemedicine and remote monitoring systems

---

## 🚀 Future Scope

* 📱 Mobile app integration for alerts
* ☁️ Cloud-based monitoring dashboard
* 🤖 AI-based predictive apnea detection
* 👶 Multi-infant monitoring system
* 📊 Data analytics for healthcare insights

---

## 👨‍💻 Team Members

* Sudiksha Shailesh Sawant
* Om Deepak Rane

---

## 🏫 Institution

Sardar Patel Institute of Technology, Mumbai

---

## 🏆 Project Domain

Intelligent & Autonomous Engineering Systems

---

## 📸 Demo

*(Add images/videos here)*

---

## 📚 References

* S. Ahani et al., *Video-Based RR Estimation for Infants*, IEEE J. Transl. Eng. Health Med., 2024
* J. Jorge et al., *Non-Contact Monitoring of Respiration in NICU*, IEEE FG Conference, 2017
* S. Sharma et al., *Automated Detection of Newborn Sleep Apnea*, ICAPR, 2015
* OpenCV Documentation: https://opencv.org
* ESP32 Datasheet: https://documentation.espressif.com
* WHO Neonatal Mortality Reports: https://data.who.int

---

## 🙌 Acknowledgment

We sincerely thank our mentors and institution for their guidance and support in developing this project.

---

## ⭐ Contribution

Feel free to fork, improve, and contribute to this project!

---
