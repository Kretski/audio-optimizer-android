# Audio Optimizer – Adaptive On-Device Audio Processing for Android
Major Update Incoming — Tiny AutoFUS v2

We are moving beyond static audio enhancement.

The next version of Audio Optimizer evolves into a context-aware edge AI signal adaptation system powered by Tiny AutoFUS v2.

✨ What’s new

🧠 Environment Profiling
The system now captures a short acoustic fingerprint and adapts its DSP strategy depending on environmental characteristics (room reflections, noise conditions, open vs enclosed spaces).

⏱ Temporal Adaptation Layer
AI decisions are stabilized over time using smoothing and adaptive-rate control, turning the model into a real-time signal control loop rather than a simple inference block.

📊 Signal Health Monitor
New internal metrics track clipping probability, noise floor drift, and dynamic range behavior — enabling AI-driven signal integrity management.

🔁 Model Hot-Swap Architecture
The neural controller is now modular, allowing future TinyML models to plug into the DSP pipeline without architectural changes.

🎯 Direction

This update shifts the project from an “AI audio app” to a reference implementation of ultra-light edge AI for adaptive signal processing.

Still:

Fully offline

~25 KB neural model

Real-time operation

Runs on standard Android hardware

More details coming soon.
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
