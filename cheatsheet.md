# 🧪 SSL Pinning Bypass Cheatsheet

This file explains how to bypass SSL Pinning in Android apps using multiple methods.

---

### 🛠️ 1. Using Objection
```bash
objection -g com.app.package explore
android sslpinning disable

🔬 2. Using Frida (OkHttp bypass)
bash
frida -U -n com.target.app -l frida-scripts/bypass-okhttp.js


📲 3. Magisk SSLUnpin Module
Flash the Magisk module MagiskTrustUserCerts.zip
Reboot device
Now user-installed certs are trusted system-wide

📚 Tested Apps
DVIA-v2
InsecureBankv2
