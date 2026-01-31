# Audio Optimizer – Adaptive On-Device Audio Processing with Tiny AutoFUS

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin + C++](https://img.shields.io/badge/Language-Kotlin%20%7C%20C%2B%2B-blue)
![License](https://img.shields.io/badge/License-MIT-orange)
![APK Available](https://img.shields.io/badge/APK-Download-brightgreen)

**Audio Optimizer** is an Android application that performs real-time adaptive audio equalization using a lightweight neural model (**Tiny AutoFUS**) running directly on-device. No internet, no cloud — just intelligent audio at the edge.

Perfect for:
- Real-time voice and media enhancement  
- Embedded acoustic systems (drones, marine tech, industrial monitoring)  
- Privacy-first audio processing  

---

## 📲 Try It Now – Download APK

A pre-built demo APK is available for immediate testing:

📥 [**Download `audio_optimizer_v1.0.apk`**](https://github.com/Kretski/audio-optimizer-android/releases/latest)  
*(Tap to install on Android 8.0+)*

> 🔒 The app runs entirely offline. No data leaves your device.

---

## 🔊 System-Wide Audio Capture (No Microphone Needed)

Audio Optimizer processes **live system audio** from any application — including **YouTube, Spotify, games, calls, and more** — without using the microphone.

- Uses Android’s standard **MediaProjection API** (same mechanism as screen recording apps)  
- Requires **one-time user approval** (no root, no special hardware)  
- Works on most Android 10+ devices (Pixel, Samsung, OnePlus, etc.)  

> ℹ️ This enables true on-device audio enhancement across all apps — a rare capability in mobile audio processing.

---

## 🔍 Key Features

- ✨ **Adaptive EQ for all audio sources** – responds to live content from any app  
- 🧠 On-device AI: Powered by **Tiny AutoFUS** (25 KB neural model, PyTorch Lite)  
- ⚡ Low-latency DSP: Native C++ Biquad filters, FFT analysis, noise-aware gain  
- 📁 Built-in WAV export for calibration and offline analysis  
- 📵 **100% offline** – no internet, no cloud, no telemetry  
- 📱 Lightweight (~1.2 MB APK), compatible with Android 8.0+  

---

## 🛠️ Build from Source

### Requirements
- Android Studio (with NDK & CMake)  
- JDK 11+  
- Android SDK ≥ API 24  

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Kretski/audio-optimizer-android.git
  Open in Android Studio
Build and deploy to device
💡 The neural model (tiny_autofus.ptl) is included in the assets/ folder.
📜 License
MIT License – free for personal and commercial use. See LICENSE.
🤝 Collaboration
If you work with audio systems, embedded AI, or scientific signal processing — let’s talk.
This project is part of the AZURO AI Platform, focused on interpretable, edge-deployable intelligence.
→ Explore AZURO CREATOR: Automated Scientific Discovery
