# Audio Optimizer – Adaptive On-Device Audio Processing for Android

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin + C++](https://img.shields.io/badge/Language-Kotlin%20%7C%20C%2B%2B-blue)
![License](https://img.shields.io/badge/License-MIT-orange)
![APK Available](https://img.shields.io/badge/APK-Download-brightgreen)

**Audio Optimizer** is a lightweight Android app that applies real-time adaptive equalization to your device’s audio — all processed locally, with no internet or cloud required.

Unlike static EQs, it **dynamically adjusts** based on live audio content, enhancing clarity and balance whether you're listening to music, watching videos, or on a call.

---

## 📲 Try It Now

📥 [**Download `audio_optimizer_v1.0.apk`**](https://github.com/Kretski/audio-optimizer-android/releases/latest)  
*(Works on Android 8.0+)*

> 🔒 100% offline — no data collection, no telemetry.

---

## 🔊 Works with All Apps — No Microphone Needed

Audio Optimizer captures **system audio directly** from your device — not through the microphone.

✅ Compatible with:  
- YouTube  
- Spotify  
- Netflix  
- Games  
- Phone calls  
- Any app producing sound  

How?  
→ Uses Android’s built-in **MediaProjection API** (same as screen recording apps)  
→ Requires **one-time user approval** (no root, no special permissions)  
→ Supported on most Android 10+ devices

---

## 🔍 Features

- Real-time adaptive equalization  
- On-device neural processing (25 KB model)  
- Low-latency native DSP: Biquad filters, FFT, noise-aware gain  
- Built-in WAV export for analysis  
- Lightweight (~1.2 MB APK)  
- Fully offline, privacy-first design  

---

## 🛠️ Build from Source

### Requirements
- Android Studio (with NDK & CMake)  
- JDK 11+  
- Android SDK ≥ API 24  

### Steps
```bash
git clone https://github.com/Kretski/audio-optimizer-android.git
