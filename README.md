# 🧠 IbrainsCat-Core v1.0.4

> “I don’t download tools.  
> I build systems.”

**IbrainsCat** is a custom hacking terminal environment created inside Termux using Python.  
It includes tools for recon, payload building, and Telegram-based reporting — built by **Ismail (aka @ibrainsCat)**.

---

## 🚀 Features

- 🔐 Terminal login with access key
- 🛰️ Recon scanner (OS guessing + open port detection)
- 📤 Telegram integration for auto log delivery
- 📦 Payload builder (Android reverse shell APK via `msfvenom`)
- 📁 Hidden log + payload storage in `.ibrainscat`
- 🎨 Styled CLI with `figlet`, `toilet`, `colors`

---

## 📂 Installation

### 📦 Prerequisites:
```bash
pkg install unzip python toilet figlet metasploit -y
pip install requests
