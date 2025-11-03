# 🔐 SSL Pinning Bypass — Facebook App (Educational Demo)

This repository demonstrates how SSL/TLS **certificate pinning** works in the Facebook Android app, along with a **practical educational example** of controlled, authorized bypass techniques for research and testing purposes only.

> ⚠️ **Disclaimer:**  
> This project is strictly for **educational and authorized security research**.  
> Do **not** use it for unauthorized activities. The author assumes **no responsibility** for misuse.

---

## 🎥 Demo Video

▶️ [Watch the demonstration](https://github.com/user-attachments/assets/2a4b5b84-02dd-420a-bc91-5966de171f43)

---

## ⚙️ Supported Architectures
- **arm64 / aarch64**

---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)

---

## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator

---

## 🚀 Bypass Procedure

1. Replace the patched library file:
   ```bash
   adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so
