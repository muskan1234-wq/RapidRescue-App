# 🚀 RapidRescue – Smart Accident Detection & Emergency Alert System

## 📌 Overview
RapidRescue is a smart Android application designed to automatically detect accidents and send emergency alerts in real time. The app helps users get immediate assistance by notifying emergency contacts with live location, call alerts, and SMS messages.

It is built using Java and integrates hardware support (Arduino + sensors) for real-world accident detection.

---

## ✨ Key Features

👤 User Management  
- Secure user registration and login  
- Profile management  

🚨 Accident Detection System  
- Automatic accident detection using sensors / hardware integration  
- Vibration alert when accident is detected  
- "I am OK" safety confirmation feature  

📍 Emergency Alert System  
- Sends automatic SMS to emergency contacts  
- Makes automatic calls to saved contacts  
- Shares live GPS location  

📞 Emergency Contacts  
- Add up to 5 emergency contacts  
- Manage, edit, or delete contacts  

🔗 Connectivity  
- Bluetooth integration with Arduino (HC-05 / ESP32)  
- Real-time data communication between hardware and app  

---

## 🧱 Tech Stack

### 📱 Android App
- Java (Android Studio)
- XML (UI Design)
- SQLite / Local Storage
- Google Location Services

### 🔧 Hardware Integration
- Arduino Uno
- MPU6050 Sensor (Acceleration Detection)
- HC-05 Bluetooth Module
- GPS Module

### 🌐 Backend (Optional)
- PHP / MySQL (for storing user data)

---

## 📂 Project Structure

RapidRescue/
│
├── app/
│ ├── java/com/rapidrescue/
│ │ ├── activities/
│ │ ├── services/
│ │ ├── adapters/
│ │ ├── utils/
│ │
│ ├── res/
│ ├── layout/
│ ├── drawable/
│ ├── values/
│
├── AndroidManifest.xml
└── build.gradle

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/rapidrescue.git
cd rapidrescue
2️⃣ Open in Android Studio
Open Android Studio

Click on Open Existing Project

Select this folder

3️⃣ Run App
Connect emulator or physical device

Click Run ▶

🔧 Hardware Setup (Optional)
Connect MPU6050 to Arduino Uno

Connect HC-05 Bluetooth module

Upload Arduino code to detect sudden acceleration

Pair Arduino with Android app via Bluetooth

📸 App Screens (Example)
Login / Registration Screen

Home Dashboard

Emergency Contacts Screen

Accident Alert Popup

Live Location Sharing Screen

🚀 Future Improvements
AI-based accident detection improvement

Cloud database integration (Firebase)

Real-time tracking for emergency services

Voice command activation

Wearable device integration

👩‍💻 Developer
Muskan Pathan
BTech Computer Science & Engineering
Project: RapidRescue – Smart Safety System

🤝 Contribution
Fork the repository

Create feature branch

Commit changes

Open Pull Request

📄 License
This project is for educational and personal use only.

yaml
Copy code

---

# 🎯 Agar tum chaho
Main tumhare RapidRescue ke liye:
✔ GitHub repository setup  
✔ professional banner image  
✔ app screenshots layout  
✔ resume description (1-liner + full project description)  

bhi bana dunga 👍
