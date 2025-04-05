# 🚩 FlagSeer

![FlagSeer Logo](flagseer_logo.png)

**FlagSeer** is a mobile application that uses the device's camera to detect and interpret maritime signal flags in real-time. It helps sailors, port authorities, and sea enthusiasts understand navigational signals directly from their surroundings using AI and computer vision.

---

## 📱 Platforms

- ✅ Android (Kotlin)
- ✅ iOS (Swift)
- 🔜 Cross-platform version (Flutter / React Native – in progress)

---

## 🎯 Features

- 📷 Live camera preview
- 🧠 On-device AI model (TFLite) for recognizing maritime signal flags
- 🌊 Interpretation of signals using the International Code of Signals (ICS)
- 🛟 Designed for offline use and maritime environments

---

## 🗂 Project Structure

```
FlagSeer/
├── android/           # Android Kotlin code
│   ├── MainActivity.kt
│   └── activity_main.xml
├── ios/               # iOS Swift code
│   ├── FlagSeerApp.swift
│   └── CameraView.swift
├── model/
│   └── flag_model.tflite  # Trained TFLite model (placeholder)
└── README.md
```

---

## ⚙️ Getting Started

### 📦 Android (Kotlin)

1. Open the `android/` folder in Android Studio.
2. Make sure `CameraX` dependencies are added in `build.gradle`.
3. Add your `.tflite` model to the assets folder.
4. Run the app on your Android device.

### 🍎 iOS (Swift)

1. Open the `ios/` folder in Xcode.
2. Grant camera permissions in `Info.plist`.
3. Run on a real iOS device.

---

## 🧠 Model

The app uses a custom-trained TensorFlow Lite model to recognize maritime signal flags (A-Z). You can retrain the model with custom datasets using TensorFlow and export as `.tflite`.

> **Model file:** `/model/flag_model.tflite`

---

## 📸 Sample Use Case

- Point your phone’s camera toward a ship displaying signal flags.
- The app recognizes each flag and provides its meaning (e.g., *“Man Overboard”*, *“I require assistance”*).
- Works offline at sea.

---

## 🧑‍💻 Developer

**Mehmet Turgay AKALIN**  
📍 [https://github.com/makalin](https://github.com/makalin)

---

## 🛠️ License

This project is licensed under the MIT License.

---

## 🌊 Let's build smarter seas with FlagSeer.
