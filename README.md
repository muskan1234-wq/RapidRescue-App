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
- Automatic accident detection using MPU6050 sensor / hardware integration  
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


## 📂 Project Structure

📦 RapidRescue
┣ 📂 app
┃ ┣ 📂 java/com/rapidrescue
┃ ┃ ┣ 📂 activities
┃ ┃ ┣ 📂 services
┃ ┃ ┣ 📂 adapters
┃ ┃ ┗ 📂 utils
┃ ┣ 📂 res
┃ ┃ ┣ 📂 layout
┃ ┃ ┣ 📂 drawable
┃ ┃ ┗ 📂 values
┣ 📜 AndroidManifest.xml
┗ 📜 build.gradle


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/rapidrescue.git
cd rapidrescue
2️⃣ Open in Android Studio
Open Android Studio

Click Open Existing Project

Select project folder

3️⃣ Run App
Connect emulator or physical device

Click ▶ Run



🚀 Future Improvements
AI-based accident detection system

Firebase cloud integration

Real-time tracking for ambulance/police

Voice command activation

Wearable device integration

👩‍💻 Developer
Muskan Pathan
BTech Computer Science & Engineering
Project: RapidRescue – Smart Safety System

🤝 Contribution
Fork repository

Create feature branch

Commit changes

Open Pull Request

