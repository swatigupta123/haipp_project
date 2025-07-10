# 🧒📱 Haipp – Parental Control Android App

[![Play Store](https://img.shields.io/badge/Download-Play%20Store-green?logo=google-play)](https://play.google.com/store/apps/details?id=com.tracking.haipp)

**Haipp** is a parental control and digital wellbeing app that helps parents track and manage their child’s smartphone and app usage. Built using **Java**, **Retrofit**, and **Google Maps**, it provides real-time monitoring, app blocking, screen time limits, GPS tracking, and educational task management with rewards.

---

## 📱 Key Features

- 👨‍👩‍👧 **Parental Login Dashboard**
- 📊 **App Usage Tracking** – Monitor daily screen time & app usage (e.g. Instagram, YouTube)
- 🔒 **App Blocking & Limits** – Restrict access to specific apps or websites
- ⏱️ **Daily Screen Time Control** – Set total daily screen usage limits per child
- 📍 **Real-Time GPS Tracking** – View current location of child on Google Maps
- 🚧 **Geofencing Alerts** – Get notified when child enters/exits defined areas
- 🎯 **Study Mode** – Temporarily block distractions during study hours
- 🎁 **Reward System** – Assign educational tasks, reward good behavior with screen time or points

---

## 🧩 Tech Stack

| Layer              | Technologies Used              |
|-------------------|----------------------------------|
| Language           | Java                            |    |
| Networking         | Retrofit                        |
| Location Services  | Google Maps + FusedLocation API |
| Background Tasks   | Service           |
| Data Storage       | SharedPreferences      |
| Notifications      | Firebase Cloud Messaging (FCM)  |
| Backend            | REST API (Java/PHP/Laravel etc.)|

---

## 📷 Screenshots

| Home (Parent) | App Usage | GPS Location | Study Task |
|---------------|-----------|--------------|-------------|
| ![](screenshots/login.png) | ![](screenshots/Location_History.png) | ![](screenshots/task.png) | ![](screenshots/activity_report.png) |


---

## 🚀 How It Works (Flow)

1. **Parent registers & logs in**
2. Adds child account & connects their device
3. App usage is tracked in background
4. Location & app data sent via REST API to backend
5. Parent receives updates, controls apps, and sets study tasks

---

## 📈 Future Enhancements

-  Temporary block app usage via push command
-  Offline sync with Room database
-  Parent-child chat system


---

##  Developed By

**Swati Gupta**  
Android Developer | 2.4+ Years Experience  
[GitHub]((https://github.com/swatigupta123/)) • [LinkedIn](https://linkedin.com/in/YOUR_LINK)

---

## 🛡️ License

This app is proprietary and developed for commercial distribution via the Play Store. All rights reserved.
