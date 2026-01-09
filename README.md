# 🔐 SSL Pinning Bypass — Facebook App

This repository show how to Bypass Facebook SSL Pinning and intercept Facebook HTTPS Traffic.
---

## 🎥 Demo Video

▶️ [Watch the demonstration](https://github.com/user-attachments/assets/bae8f052-1a4f-4651-8632-1321794cc08e)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Facebook App Version 
- **543.0.0.55.73**
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

1. Replace patched `libcoldstart.so with /data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

keyword : 脸书 SSL 固定 旁路, 
تجاوز تثبيت شهادة SSL على فيسبوك

## For latest patched libcoldstart.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
