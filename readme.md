# SSL Pinning Bypass Facebook 
A practical demonstration of bypassing SSL/TLS certificate pinning in the Facebook Android app for educational and authorized security research purposes.

# 🎥 Demo Video

![Click here to watch the demo video](https://github.com/MUH4MM4D-SH4KIB/SSL-Pinning-Bypass-Facebook/blob/main/fbsslbypass.mp4)

# Architecture must be **arm64**/**aarch64**

# Requirements for Mobile Phone
- Android device Rooted or Non Rooted
- Proxypin or Reqable 

# Requirements for Emulator 
- Windows with Reqable / Brup Suite / Mitmproxy installed.
- Android Emulator (Nox / LDPlayer)
- Root access in Emulator

# Bypassing Process
- Replace patched `libcoldstart.so with /data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
- Use this Command : `adb push D:\patched\libcoldstart.so /data/data/com.facebook.katana/lib-compressed/libcoldstart.so`
- Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

# For latest patched libcoldstart.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>

