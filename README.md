<p align="center">
  <img src="https://raw.githubusercontent.com/wiki/gemini/generative-ai-dart/assets/logo.png" alt="Beykoz University Logo" width="150">
</p>

<h1 align="center">🎓 Beykoz University App</h1>

<p align="center">
  <strong>The official mobile application for Beykoz University, built with Flutter.</strong><br>
  Providing students, teachers, and staff easy access to university services and information.
</p>

---

## ✨ Features

* 🔐 **Authentication**: Secure login using Firebase Authentication.
* 🏠 **Home Screen**: Customizable dashboard with frequently used features and university announcements.
* 📰 **News Feed**: Stay updated with the latest university news and events.
* 👤 **Profile**: View personal information (scraped from OIS), including GPA and profile picture.
* ✔️ **Attendance System**: Bluetooth Low Energy (BLE) based system.
    * 🧑‍🏫 Teachers start sessions & broadcast codes.
    * 🧑‍🎓 Students join by scanning & entering codes.
* 🌐 **Web Portals**: Integrated WebView for OIS and Online Beykoz.
* 💬 **Messenger**: In-app chat functionality.
* 🏢 **University Info**:
    * 👨‍🏫 Academic Staff: Browse faculty members & access CVs.
    * 🚌 Transportation & Contact: Campus locations & contact details.
* 🎨 **Customization**:
    * ⭐ Edit Favorites: Personalize the home screen quick access.
    * 🌓 Dark Mode: Supports light and dark themes.
* ⚙️ **Admin Panel (Developer Role)**: Manage users, teachers, courses, and departments.

---

## 🛠️ Key Technologies

* **📱 Flutter**: Cross-platform UI toolkit.
* **🔥 Firebase**:
    * **Authentication**: User login.
    * **Cloud Firestore**: Data storage (roles, courses, attendance, etc.).
* **🧩 Provider**: State management.
* **🔵 Bluetooth Low Energy (BLE)**: Attendance system (`flutter_reactive_ble` & native).
* **🕸️ WebView**: In-app web browsing (`webview_flutter`).
* **💾 Shared Preferences**: Local storage for theme & favorites.

---

## 📁 Project Structure