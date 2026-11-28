<div align="center">

![Aliensoft AI WhatsApp Assistant Pro](docs/banner.png)

# Aliensoft AI WhatsApp Assistant Pro — Public Releases

**Native Windows 10/11 (x64) Autonomous WhatsApp AI Agent, Order Engine & CRM Suite**  
Built by **[Alien Software Development](https://aliensoftwaredevelopment.com)** · Dhaka, Bangladesh

[![Download Latest Release](https://img.shields.io/badge/Latest_Release-v1.0.8_Windows_x64-16A34A?style=for-the-badge&logo=windows)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)
[![Download Setup EXE](https://img.shields.io/badge/Download-Setup_Installer_(.exe)-2563EB?style=for-the-badge)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)
[![Download Portable ZIP](https://img.shields.io/badge/Download-Offline_Portable_(.zip)-0284C7?style=for-the-badge)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)
[![Auto-Update](https://img.shields.io/badge/Auto--Update-GitHub_Releases-7C3AED?style=for-the-badge)](#automatic-updates)

</div>

---

## Official Public Distribution Repository

Download the official **Windows Setup Installer (`.exe`)** or **Offline Portable (`.zip`)** directly from GitHub Releases — zero external runtime installs needed (`.NET 10` and bridge runtimes are bundled inside). Complete source code is maintained privately by Alien Software Development.

> **[Download Latest Release (`releases/latest`)](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**

---

## Two Ways to Install (Windows 10 / 11 x64)

### Option 1: Windows Setup Installer `.exe` *(Recommended)*
1. Download **`AliensoftAssistant_Setup_x64_<version>_SelfContained.exe`** from **[Releases](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**.
2. Run the setup wizard (creates Desktop + Start Menu shortcuts and optional Windows tray startup).
3. Launch **ALIENSOFT AI WHATSAPP ASSISTANT** — future releases on this repository download and install automatically!

### Option 2: Zero-Install Offline Portable `.zip`
1. Download **`Aliensoft-AI-WhatsApp-Assistant-Offline-Portable-win-x64.zip`** from **[Releases](https://github.com/alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases/releases/latest)**.
2. Extract all files into a permanent folder (e.g. `C:\Aliensoft\WhatsAppAssistant\`).
3. Run **`Aliensoft.Assistant.Desktop.exe`**.

---

## Key Capabilities & Enterprise Modules

| Capability | Highlights |
| :--- | :--- |
| **Self-Learning Local Brain + External LLMs** | Offline bilingual (`English`, `বাংলা`, `Banglish`) `LocalAIBrain` + `AgentMemoryService` that auto-learns from connected AI providers (**Ollama**, **FreeLLM**, **Gemini**, **OpenAI**, **DeepSeek**, **Groq**) and human operator edits. |
| **Voice Note & Image AI Understanding** | Automatically transcribes voice notes and inspects customer images grounded in your live product catalog, services, FAQs, and chat history. |
| **Company Setup & Mobile WhatsApp UX** | Configure full business identity, address, hours, contacts, and delivery/payment rules; sends clean mobile-friendly WhatsApp cards with section icons and divider lines. |
| **Order Booking Engine & REST API** | Collects customizable required order topics (**Name**, **Mobile**, **Product**, **Qty**, **Shipping Address**, **Payment Method**, custom fields) and saves to **Internal SQLite DB**, **HTTP API Script**, or **External SQL Table** (`Oracle`, `MySQL`, `MS SQL`, `PostgreSQL`, `SQLite`), with `/api/internal/orders` REST API for external ERP/POS apps. |
| **Pro Products Catalog & Encrypted Photos** | Full table list with inline **Active/Deactive** toggles, popup **Add/Edit** modal in both Desktop and Web Console, and Windows DPAPI binary encrypted product photos. |
| **Doctor Directory & Multi-DB Appointments** | Pasted `CREATE TABLE` DDL parsing & live doctor directory lookups alongside strict non-appointment chat isolation. |
| **Dual WhatsApp Gateways & Mobile Web Console** | Embedded **QR Web Engine** + Official **Meta Cloud API** + Cloudflare Tunnel + protected mobile-responsive Browser Workspace (`http://127.0.0.1:5085/`) with bottom quick navigation. |
| **200+ Automation Rules & 30-Day Free Trial** | Preloaded bilingual rules (`[AR-001]`–`[AR-200]`) and hardware-bound ECDSA P-256 licensing with automatic 30-day free trial. |

---

## Automatic Updates

- Every installation checks `alien-software-development/Aliensoft-AI-WhatsApp-Assistant-Releases` **8 seconds after startup** and every **4 hours** while running in the background.
- When a newer version is published, the updater automatically:
  1. Verifies the matching package (`Setup .exe` or `Portable .zip`) against its **`.sha256` checksum**.
  2. Downloads and stages the verified upgrade cleanly.
  3. Preserves all local settings, rules, orders, and data under `%LOCALAPPDATA%\Aliensoft\WhatsAppAssistant\`, installs, and relaunches.

---

## Clean-Install & Security Guarantee

- **Zero Secrets Shipped**: Automated pre-package verification guarantees zero developer API keys, SQLite databases, inbox messages, WhatsApp sessions, or private keys are ever distributed.
- **Verify Package Checksum (PowerShell):**
  ```powershell
  Get-FileHash .\AliensoftAssistant_Setup_x64_*.exe -Algorithm SHA256
  ```

---

## Security & Support

- Security Architecture & Responsible Disclosure: [SECURITY.md](SECURITY.md)
- Portal: **[aliensoftwaredevelopment.com](https://aliensoftwaredevelopment.com)**
- WhatsApp Hotline & Live Demo: **[+880 1710-978997](https://wa.me/8801710978997)**
- Email: **aliensoftwaredevelopment@gmail.com**
