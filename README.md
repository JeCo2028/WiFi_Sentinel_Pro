# 🛡️ WiFi Sentinel Pro

<p align="center">
  <img src="static/icon-512.png" alt="WiFi Sentinel Pro Logo" width="128" height="128" style="border-radius:24px; box-shadow:0 8px 24px rgba(56,189,248,0.3);"/>
</p>

<p align="center">
  <strong>Next-Generation Standalone Wi-Fi Management, Device Sentinel & Router Controller</strong><br>
  <em>Available for Windows Desktop and Standalone Android Mobile</em>
</p>

---

## 🌟 Overview

**WiFi Sentinel Pro** provides complete network monitoring and router management across desktop and mobile devices.

- **📱 Standalone Android App (`WiFiSentinelPro.apk`):** Operates 100% solo without requiring a PC server. Automatically connects to your local Wi-Fi router gateway, provides instant router administration, and includes an on-device subnet scanner to discover connected devices.
- **💻 Windows Desktop Application (`WiFiSentinelPro_v1.0_Setup.exe`):** Full-featured desktop network sentinel featuring real-time bandwidth traffic analytics, device discovery, vendor identification, and network protection.

---

## 🚀 Key Features

### 📱 Android Mobile Edition (100% Solo Standalone)
- **Zero Computer Dependency:** Operates independently directly from your phone.
- **Auto-Detect Router Gateway:** Automatically discovers gateway IPs (`192.168.101.1`, `192.168.1.1`, `192.168.0.1`, etc.).
- **Built-in Subnet Device Scanner:** High-speed multi-threaded ping and port sweep to detect active phones, laptops, and smart devices.
- **Direct Router Panel Access:** Responsive interface with custom user-agent and zoom controls.

### 💻 Windows Desktop Edition
- **Live Network Sentinel:** Instant discovery of active devices, IP addresses, MAC vendors, and real-time packet speeds.
- **Standalone Installer:** Built with Inno Setup with zero external runtime prerequisites.
- **Cross-Platform QR Pairing:** Displays local download links and QR codes to easily distribute the APK across your Wi-Fi network.

---

## 📦 Downloads & Installation

Visit the [Releases](https://github.com/JeCo2028/WiFi-Sentinel-Pro/releases) page to download the latest builds:

| Platform | Download Package | Description |
| :--- | :--- | :--- |
| **Android** | [`WiFiSentinelPro.apk`](https://github.com/JeCo2028/WiFi-Sentinel-Pro/releases/latest/download/WiFiSentinelPro.apk) | Standalone mobile app for router control & Wi-Fi scanning |
| **Windows** | [`WiFiSentinelPro_v1.0_Setup.exe`](https://github.com/JeCo2028/WiFi-Sentinel-Pro/releases/latest/download/WiFiSentinelPro_v1.0_Setup.exe) | Complete desktop setup wizard for Windows 10/11 |

---

## 🛠️ Project Structure

```text
WiFi-Sentinel-Pro/
├── android-app/             # Standalone Android native project (Kotlin/Gradle)
│   └── app/src/main/        # Native Router Controller & Network Scanner
├── RELEASES_UPLOAD/         # Ready-to-publish production binaries (.apk, .exe)
├── static/                  # Responsive web dashboard assets & icons
├── templates/               # Dashboard templates
├── server.py                # Core desktop server engine
├── scanner.py               # Network packet analyzer and device detector
├── controller.py            # Device blocking and traffic management
└── installer.iss            # Inno Setup compilation script
```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
