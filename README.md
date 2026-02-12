# Facebook SSL Pinning Bypass for Android (2026) – Intercept & Capture HTTPS Traffic

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64--v8a-Supported-blue?style=for-the-badge)
![x86_64](https://img.shields.io/badge/x86__64-Supported-blue?style=for-the-badge)

> Bypass Facebook SSL certificate pinning on Android by patching `libcoldstart.so` — intercept, inspect, and analyze HTTPS network traffic on both **rooted** and **non-rooted** devices.

---

## 📖 Overview

This project provides a **patched `libcoldstart.so`** library for the Facebook Android app with SSL/TLS certificate pinning disabled, enabling security researchers and developers to capture and analyze Facebook HTTPS traffic using standard MITM proxy tools.

**Key highlights:**

- ✅ Works on rooted and non-rooted Android devices
- ✅ Compatible with Android emulators (Nox, LDPlayer)
- ✅ Works with popular proxy tools (Burp Suite, Mitmproxy, Reqable, Proxypin)
- ✅ ARM64-v8a & x86_64 architecture support
- ✅ Simple library replacement — no full APK repackaging needed

---

## 🎥 Proof of Concept

<img width="720" height="1640" alt="Facebook SSL Pinning Bypass - Traffic Interception Screenshot" src="https://github.com/user-attachments/assets/48a87157-a625-459a-bba6-ee831b45bd50" />

▶️ [**Watch the Full Video Demonstration**](https://github.com/user-attachments/assets/5ba22ef4-0bff-4d01-92fd-bcf31be40138)

---

## 📋 Supported Facebook Version

| App | Version | Patched Library | Status |
|-----|---------|-----------------|--------|
| Facebook | **547.0.0.41.68** | `libcoldstart.so` | ✅ Bypassed |

> For the **latest patched `libcoldstart.so`**, [contact me on Telegram](https://t.me/MUH4MM4DSH4KIB).

---

## ⚙️ Supported Architectures

| Architecture | Support |
|---|---|
| `arm64-v8a` | ✅ |
| `x86_64` | ✅ |

---

## 📱 Requirements

### Option A: Physical Android Device

- Android phone or tablet (**rooted or non-rooted**)
- A traffic interception proxy tool:
  - [Proxypin](https://proxypin.com) — free, lightweight
  - [Reqable](https://reqable.com) — feature-rich, modern UI

### Option B: Android Emulator (PC)

- Windows PC with one of the following emulators installed:
  - [Nox Player](https://www.bignox.com/) — root access enabled
  - [LDPlayer](https://www.ldplayer.net/) — root access enabled
- A desktop MITM proxy tool:
  - [Burp Suite](https://portswigger.net/burp) — industry standard
  - [Mitmproxy](https://mitmproxy.org/) — open source
  - [Reqable](https://reqable.com)
  - [Proxypin](https://proxypin.com)

> **Note:** Root access must be enabled in the emulator to replace the native library.

---

## 🚀 Bypass Procedure

### Step 1 — Push the Patched Library

Replace the original `libcoldstart.so` with the patched version using ADB:

```bash
adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so
```

### Step 2 — Set Correct Permissions (if needed)

```bash
adb shell chmod 755 /data/data/com.facebook.katana/lib-compressed/libcoldstart.so
```

### Step 3 — Configure Your Proxy

Set up your preferred MITM proxy tool (Proxypin, Reqable, Burp Suite, or Mitmproxy) and install/trust its CA certificate on the device or emulator.

### Step 4 — Launch & Capture

Open the Facebook app and start intercepting HTTPS requests and responses in your proxy tool.

> **Tip:** Force-stop Facebook before launching it after the library replacement to ensure the patched library is loaded.

---


**Target path:**
```
/data/data/com.facebook.katana/lib-compressed/libcoldstart.so
```

---

## ❓ FAQ

**Q: Does this require root access?**
A: On physical devices, it works on both rooted and non-rooted setups. On emulators, root access is needed to write to the app's private data directory.

**Q: Will this work on iOS?**
A: No. This bypass targets the Android version of Facebook only.

**Q: Can I use this with Burp Suite?**
A: Yes. Configure Burp Suite as a proxy, install the Burp CA certificate on your device/emulator, push the patched library, and launch Facebook.

**Q: Do I need to repackage or re-sign the APK?**
A: No. This method replaces only the native `.so` library — no APK modification or re-signing required.

**Q: The patched version doesn't match the latest Facebook release — what do I do?**
A: [Contact me on Telegram](https://t.me/MUH4MM4DSH4KIB) for the latest patched `libcoldstart.so`.

---

## 📬 Contact & Latest Builds

For the **most up-to-date** patched `libcoldstart.so` for Facebook, reach out directly:

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)

---

## 🏷️ Tags

`facebook ssl pinning bypass` · `facebook certificate pinning` · `facebook mitm` · `facebook traffic interception` · `facebook burp suite` · `facebook proxy android` · `facebook https decrypt` · `meta facebook security` · `android ssl bypass no root` · `libcoldstart.so patch` · `facebook api reverse engineering` · `facebook ssl bypass 2025`
