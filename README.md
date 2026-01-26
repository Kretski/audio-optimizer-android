# Audio Optimizer – Adaptive On-Device Audio Processing with Tiny AutoFUS

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin + C++](https://img.shields.io/badge/Language-Kotlin%20%7C%20C%2B%2B-blue)
![License](https://img.shields.io/badge/License-MIT-orange)
![APK Available](https://img.shields.io/badge/APK-Download-brightgreen)

**Audio Optimizer** is an Android application that performs real-time adaptive audio equalization and enhancement using a lightweight neural model (**Tiny AutoFUS**) running directly on-device. No internet, no cloud — just intelligent audio at the edge.

Perfect for:
- Real-time voice/audio enhancement
- Embedded acoustic systems (drones, marine tech, industrial monitoring)
- Privacy-first audio processing

---

## 📲 Try It Now – Download APK

A pre-built demo APK is available for immediate testing:

📥 [**Download `audio_optimizer_v1.0.apk`**](./releases/latest)  
*(Tap to install on Android 8.0+)*

> 🔒 The app runs entirely offline. No permissions beyond microphone access are required.

---

## 🔍 Features

- Real-time adaptive EQ based on learned audio profiles
- On-device inference with `tiny_autofus.ptl` (PyTorch Lite)
- Low-latency native DSP: Biquad filters, FFT, noise gate
- WAV export for analysis & calibration
- Designed for edge devices (phones, tablets, embedded Android)

---

## 🛠️ Build from Source

### Requirements
- Android Studio (with NDK & CMake)
- JDK 11+
- Android SDK ≥ API 24

### Steps
1. Clone:
   ```bash
   git clone https://github.com/your-username/audio-optimizer-android.git
