> ⚠️ **WORK IN PROGRESS (WIP)**  
> This project is currently in early development and is **not functional yet**.  
> Features, database schemas, and code structure are subject to rapid change.
> # 🚀 AkezhanMessenger Preview

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Android-green.svg)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-purple.svg)
![Backend](https://img.shields.io/badge/Backend-Supabase-emerald.svg)

**AkezhanMessenger Preview** is a lightweight, private, and open-source Android messaging application built on modern Android architecture with Supabase serving as the realtime backend.

---

## 📱 Features

- ⚡ **Realtime Messaging:** Instant message delivery powered by WebSockets (Supabase Realtime).
- 🛡️ **Security & Privacy:** Database logic is protected with Row Level Security (RLS) policies.
- 🎨 **Modern UI:** Built in Kotlin following official Android development standards.
- 🔓 **100% Free & Open Source:** Zero proprietary trackers or closed libraries. Fully prepared for F-Droid packaging.

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **Platform:** Android SDK (Android Studio)
- **Backend:** [Supabase](https://supabase.com/) (PostgreSQL, Auth, Realtime Engine)
- **Network Client:** Ktor Client / OkHttp
- **Asynchronous Work:** Kotlin Coroutines & Flow

---

## 🚀 Quick Start

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/AkezhanWithMotorola/AkezhanMessenger-Preview.git
cd AkezhanMessenger-Preview
```

### 2. Open in Android Studio

1. Download and install [Android Studio](https://developer.android.com/studio)
2. Open the project in Android Studio
3. Wait for Gradle to sync dependencies

### 3. Configure Supabase

1. Create a project on [Supabase](https://supabase.com/)
2. Obtain your Supabase URL and API key
3. Update your configuration files with these credentials

### 4. Build and Run

```bash
./gradlew build
./gradlew installDebug
```

---

## 📖 Project Structure

```
AkezhanMessenger-Preview/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/             # Kotlin source code
│   │   │   ├── res/              # Android resources (layouts, drawables, etc.)
│   │   │   └── AndroidManifest.xml
│   │   └── test/                 # Unit tests
│   ├── build.gradle              # App-level Gradle configuration
│   └── proguard-rules.pro
├── build.gradle                  # Project-level Gradle configuration
├── gradle.properties
├── settings.gradle
├── .gitignore
├── LICENSE                       # GNU GPL v3
└── README.md
```

---

## 🔐 Security & Privacy

This project prioritizes user privacy and security:

- End-to-end encryption capabilities (configurable)
- Row Level Security (RLS) policies ensure only authorized users access data
- No analytics or tracking libraries
- All code is open-source and auditable

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for the complete license text.

---

## 👤 Author

**GitHub:** [@AkezhanWithMotorola](https://github.com/AkezhanWithMotorola)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please open an [issue](https://github.com/AkezhanWithMotorola/AkezhanMessenger-Preview/issues) on GitHub.

---

## 📞 Support

For questions or support, please reach out via GitHub Issues or contact the maintainer.

---

**Last Updated:** September 1, 2026

For the latest updates, visit the [repository](https://github.com/AkezhanWithMotorola/AkezhanMessenger-Preview).
