# 🔐 SSL Pinning Bypass Facebook

Facebook SSL Pinning Bypass for Android – intercept Facebook traffic.


## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/48a87157-a625-459a-bba6-ee831b45bd50" />


▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/5ba22ef4-0bff-4d01-92fd-bcf31be40138)


## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**

## Facebook App Version 
- **547.0.0.41.68**


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
