# 🔐 SSL Pinning Bypass Facebook

Facebook SSL Pinning Bypass and intercept Facebook Traffic.


## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/8e1d74cc-aed8-4e55-8d15-18f3e7c3fff8" />


▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/2d5dfd8c-7655-4d58-963b-295973860801)


## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**

## Facebook App Version 
- **545.0.0.43.63**


## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)


## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator


## 🚀 Bypass Procedure

1. Replace patched `libcoldstart.so with /data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libcoldstart.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
