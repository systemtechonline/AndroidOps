
# AndroidOps

> Lightweight Android command agent built for authorized device management, security research, and educational testing.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Language](https://img.shields.io/badge/Language-Java-orange)
![IDE](https://img.shields.io/badge/IDE-Android%20Studio-blue)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

---

## 📖 Overview

AndroidOps is an Android Studio project demonstrating background services,
Telegram-based command communication, and Android permission handling for
authorized environments and educational purposes.

---

## Features

- 📱 Device Status
- 📍 Location
- 🎙️ microphone 
- 📷 Camera front/back
- 👥 Contacts
- 💬 SMS
- 📂 File Manager
- 🔄 Foreground Service
- 🚀 Auto Start
- ⚡ Background Service

## Requirements

- Android Studio
- Java
- Android SDK
- Gradle
- Telegram Bot Token
- Telegram Chat ID

## Installation

```bash
git clone https://github.com/systemtechonline/AndroidOps.git
```

1. Open in Android Studio.
2. Let Gradle sync.
3. Configure your Telegram Bot credentials.
4. Build the APK.
5. Install on an authorized test device.

## Configuration

```properties
BOT_TOKEN=YOUR_BOT_TOKEN
CHAT_ID=YOUR_CHAT_ID
```
## 📋 Available Commands

| Command | Description |
|---------|-------------|
| `/alive` | Check device availability |
| `/status` | Get device information |
| `/help` | Display available commands |
| `/location` | Retrieve current location |
| `/camera` | Capture image using the rear camera |
| `/frontcam` | Capture image using the front camera |
| `/audio<seconds>` | Record audio for the specified duration (e.g., `/audio20` records for 20 seconds) |
| `/contacts` | Access contacts |
| `/sms` | Access SMS messages |
| `/files` | Browse recent gallery media |
| `/filemn` | Browse files using the file manager |

## Build

```text
Build → Build APK(s)
Build → Generate Signed Bundle / APK
```

## Tech Stack

- Java
- Android SDK
- Android Studio
- Gradle
- Telegram Bot API

## License

MIT License.

## Disclaimer

This project is intended for educational purposes, Android development practice, security research, and authorized testing only. Use it only on devices you own or are explicitly authorized to manage or evaluate.
