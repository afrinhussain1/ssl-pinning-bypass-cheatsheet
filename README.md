# 🔐 SSL Pinning Bypass Cheatsheet

A beginner-friendly collection of bypass methods, scripts, and tools to disable SSL Pinning in Android apps during mobile penetration testing.

---

## 📂 What This Project Includes
- ✅ Step-by-step SSL bypass methods
- 🧪 Frida scripts (OkHttp, WebView, etc.)
- 🛠️ Magisk patch (optional)
- 📸 Screenshots and examples

---

## 🚀 Quick Usage

Using Frida:
```bash
frida -U -n com.target.app -l frida-scripts/bypass-okhttp.js

Using Objection:
objection -g com.target.app explore
android sslpinning disable

⚠️ Disclaimer
For educational and authorized testing only.
Do not use on apps you don’t own or don’t have permission to test.
