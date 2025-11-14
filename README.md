# 🩸 BloodConnect – Blood Donation App

BloodBridge is a mobile application built to connect blood donors, recipients, hospitals, and blood banks in real time. This app helps users find and request blood, track donation history, and respond to emergencies efficiently.


## 🚀 Features

- 🔐 Firebase Authentication (Email login/register)
- 📍 Find Nearby Blood Banks & Donation Centers
- 📦 Real-time Blood Requests & Notifications
- 👤 Profile Management (Donor, Recipient, Hospital, Blood Bank)
- 📊 Donation History and Emergency Alerts
- 🌐 Fully connected to Firebase Firestore
- 📱 Android APK built using Capacitor + Android Studio

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend/Database:** Firebase Authentication & Firestore
- **Build Tools:** Capacitor
- **IDE:** Android Studio
- **Platforms:** Android

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone  https://github.com/CharishmaNelakurthi/Blood-connect-.git
cd blood-donation

### 2. Install Capacitor & Android Dependencies

npm install @capacitor/core @capacitor/cli
npm install @capacitor/android
npx cap init
npx cap add android

### 3. Build Web Assets

npm run build
npx cap copy

### 4. Open in Android Studio

npx cap open android

### 5. Build APK
Set Build Variant to release

Build → Generate Signed APK

Use app-release.apk for deployment

🔐 Firebase Configuration
Set up your Firebase project and paste your Firebase config inside:

// firebase-config.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
firebase.initializeApp(firebaseConfig);

Final APK: android/app/release/app-release.apk
Install this on Android devices to test or distribute your app.

📃 License
This project is developed for educational purposes. You are free to use or extend it with attribution.

🧑‍💻 Developed by
Charishma Nelakurthi
