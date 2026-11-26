<div align="center">

![Aliensoft AI WhatsApp Assistant Pro](docs/banner.png)

# Aliensoft AI WhatsApp Assistant Pro â€” Public Releases

**Native Windows 10/11 (x64) AI-Powered WhatsApp Automation & Smart Customer Support Suite**  
Built by **[Alien Software Development](https://aliensoftwaredevelopment.com)** Â· Dhaka, Bangladesh

[![Download Setup EXE](https://img.shields.io/badge/Download-Windows%20Installer%20(.exe)-16A34A?style=for-the-badge)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)
[![Download Portable ZIP](https://img.shields.io/badge/Download-Offline%20Portable%20(.zip)-0284C7?style=for-the-badge)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)
[![Auto-Update](https://img.shields.io/badge/Auto--Update-GitHub%20Releases-7C3AED?style=for-the-badge)](#automatic-updates)

</div>

---

## Official Public Distribution Repository

Anyone can download the official **Windows Setup Installer (`.exe`)** or **Offline Portable (`.zip`)** directly from Releasesâ€”zero external runtime installs (`.NET` and bridge runtimes are bundled inside). Source code is maintained privately by Alien Software Development.

> **[Download Latest Release (`v1.0.1`)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**

---

## Two Ways to Install (Windows 10 / 11 x64)

### Option 1: Windows Setup Installer `.exe` *(Recommended)*
1. Download **`AliensoftAssistant_Setup_x64_1.0.1_SelfContained.exe`** from **[Releases](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**.
2. Run the setup wizard (creates Desktop + Start Menu shortcuts and optional Windows tray startup).
3. Launch **ALIENSOFT AI WHATSAPP ASSISTANT** â€” future releases on this repository download and install automatically!

### Option 2: Zero-Install Offline Portable `.zip`
1. Download **`Aliensoft-AI-WhatsApp-Assistant-Offline-Portable-win-x64.zip`** from **[Releases](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**.
2. Extract all files into a permanent folder (e.g., `C:\Aliensoft\WhatsAppAssistant\`).
3. Run **`Aliensoft.Assistant.Desktop.exe`**.

---

## Automatic Updates

- Every installation checks `alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases` **8 seconds after startup** and every **4 hours** while running in the background.
- When a newer version is published (e.g., `v1.0.1`), the app automatically:
  1. Verifies the matching package (`Setup .exe` for installed apps or Portable `.zip` for portable apps) against its **`.sha256` checksum**.
  2. Downloads and stages the verified upgrade cleanly.
  3. Shuts down gracefully, installs the update while preserving all local settings, rules, and data under `%LOCALAPPDATA%\Aliensoft\WhatsAppAssistant\`, and relaunches the updated version.
- Both auto-check and auto-install can be toggled anytime in **All Settings & Preferences**.

---

## Key Capabilities & Clean-Install Guarantee

- **Voice Note & Image AI Understanding**: Automatically transcribes voice notes and analyzes images using your configured **Gemini**, **OpenAI**, or **DeepSeek** key grounded in your catalog, services, FAQs, and conversation history.
- **200+ Built-In Automation Rules**: First launch automatically seeds all **200 preset automation rules** (`[AR-001]`â€“`[AR-200]`) and a **30-day free trial**.
- **100% Clean Packages**: Automated pre-package security scanning guarantees zero developer API keys, databases, inbox chats, WhatsApp sessions, or private license files are ever shipped.
- **Verify Integrity (PowerShell):**
  ```powershell
  Get-FileHash .\AliensoftAssistant_Setup_x64_1.0.1_SelfContained.exe -Algorithm SHA256
  ```

---

## Security & Support

- Security architecture & disclosure: [SECURITY.md](SECURITY.md)
- Website: [aliensoftwaredevelopment.com](https://aliensoftwaredevelopment.com)
- WhatsApp Hotline & Support: `+880 1710-978997`
