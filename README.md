# 🔔 CloudBell

CloudBell is a student-developed smart bell and emergency notification ecosystem for educational institutions such as schools, vocational colleges, and universities.

The project was created within a STEM-based learning environment by students of a vocational education institution in Ukraine under teacher supervision.

---

## 🎯 Project Purpose

Many educational institutions still rely on outdated or manual bell systems.

In emergency situations such as air raid alerts, this can delay communication and negatively affect safety inside the institution.

CloudBell aims to:

- Automate lesson scheduling
- Provide centralized bell control
- Deliver emergency audio alerts
- Automatically conduct the Minute of Silence
- React to regional air raid alarms
- Send mobile notifications to staff and students

---

## 🧩 System Architecture

CloudBell is a distributed educational notification system consisting of:

- Desktop Application (Python): schedule logic and bell automation
- Audio Playback Node (Raspberry Pi Zero + Hi-Fi board + Volumio): audio playback for bells and announcements
- Mobile Application (Android / Java): notification delivery system

---

## 🔧 Hardware (Audio Playback Node)

The audio output subsystem is implemented as a lightweight embedded node:

- Raspberry Pi Zero (controller)
- Hi-Fi expansion board (high-quality DAC / audio output)
- Volumio firmware (audio playback and media management)

The node plays bell sounds and voice announcements through the institution’s audio system.

---

## ⚙ Technologies Used

- Python
- Java
- Android SDK
- Raspberry Pi Zero
- Hi-Fi Audio Expansion Board
- Volumio Firmware

---

## 🔗 Project Modules

Desktop Application:  
https://github.com/cloudbellproject/cloudbellapp

Android Application:  
https://github.com/cloudbellproject/cloudbellgo

---

## 👥 Project Team

### 🧑‍💻 Student Developers
- Ivan Luhvun
- Tetyana Vovk
- Anna Kravchenko
- Dominika Turday

### 👨‍🏫 Project Supervisor
Serhii Sydorenko  
Vocational Education Teacher  
Microsoft Innovative Educator Expert

---

## 🏫 Educational Context

This project was developed as part of a STEM initiative aimed at applying software engineering and problem-solving skills in real-world wartime educational conditions in Ukraine.

---

## 📄 License

MIT License
