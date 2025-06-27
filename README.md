# 🌙 Sleep Sounds App

<div align="center">

![App Logo](https://img.shields.io/badge/🌙-Sleep%20Sounds-7C3AED?style=for-the-badge&logo=moon&logoColor=white)

**A beautiful, relaxing music app designed to help you sleep better**

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)](https://dart.dev)
[![GetX](https://img.shields.io/badge/GetX-9C27B0?style=flat-square&logo=flutter&logoColor=white)](https://pub.dev/packages/get)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

### 🌟 **Transform your sleep experience with soothing sounds**

*Nature sounds • Ambient music • White noise • Sleep timer*

[📱 Download](#-download) • [✨ Features](#-features) • [🛠️ Tech Stack](#️-tech-stack) • [🌍 Languages](#-languages)

</div>

---

## 📱 Screenshots

<div align="center">
<table>
<tr>
<td align="center">
<img src="https://via.placeholder.com/250x500/667eea/ffffff?text=🌙+Home+Screen" alt="Home Screen" width="200"/>
<br><b>Home Screen</b>
</td>
<td align="center">
<img src="https://via.placeholder.com/250x500/7C3AED/ffffff?text=🎵+Music+Library" alt="Music Library" width="200"/>
<br><b>Music Library</b>
</td>
<td align="center">
<img src="https://via.placeholder.com/250x500/EAB308/ffffff?text=⏰+Sleep+Timer" alt="Sleep Timer" width="200"/>
<br><b>Sleep Timer</b>
</td>
<td align="center">
<img src="https://via.placeholder.com/250x500/667eea/ffffff?text=⚙️+Settings" alt="Settings" width="200"/>
<br><b>Settings</b>
</td>
</tr>
</table>
</div>

---

## ✨ Features

<div align="center">
<table>
<tr>
<td align="center" width="33%">

### 🎵 **Rich Sound Library**
- 🌿 Nature sounds
- 🎹 Instrumental music  
- 📻 White noise
- 🕯️ Ambient sounds
- 🧘 Meditation music
- 🎧 Binaural beats

</td>
<td align="center" width="33%">

### ⏰ **Smart Sleep Timer**
- 🔢 Multiple timer options
- ⏹️ Auto-stop functionality
- 📊 Progress visualization
- 🎚️ Fade-out effect
- 💤 Sleep-friendly design

</td>
<td align="center" width="33%">

### 🌍 **Global Experience**
- 🇺🇸 English
- 🇧🇷 Português
- 🇪🇸 Español  
- 🇫🇷 Français
- 🇩🇪 Deutsch
- 💾 Saved preferences

</td>
</tr>
</table>
</div>

### 🎯 **Additional Features**

- 🎮 **Intuitive Controls** - Simple play, pause, stop, and volume controls
- 🌙 **Dark Theme** - Eye-friendly design perfect for nighttime use
- 📱 **Responsive Design** - Optimized for all screen sizes
- 🔄 **State Management** - Smooth performance with GetX
- 💾 **Local Storage** - Your preferences are remembered
- 📢 **Ad-Supported** - Free to use with non-intrusive ads

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technology | Purpose |
|----------|------------|---------|
| **Framework** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) | Cross-platform mobile development |
| **Language** | ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) | Programming language |
| **State Management** | ![GetX](https://img.shields.io/badge/GetX-9C27B0?style=flat-square) | Reactive state management |
| **Local Storage** | ![GetStorage](https://img.shields.io/badge/GetStorage-FF6B6B?style=flat-square) | Persistent local data |
| **Audio** | ![AudioPlayers](https://img.shields.io/badge/AudioPlayers-4ECDC4?style=flat-square) | Audio playback |
| **Ads** | ![AdMob](https://img.shields.io/badge/Google%20AdMob-4285F4?style=flat-square&logo=google&logoColor=white) | Monetization |
| **Internationalization** | ![i18n](https://img.shields.io/badge/i18n-45B7D1?style=flat-square) | Multi-language support |

</div>

---

## 🏗️ Architecture

```
📱 Sleep Sounds App
├── 🎨 UI Layer (Widgets)
│   ├── HomeView
│   ├── MusicListWidget  
│   ├── PlayerControlsWidget
│   ├── TopControlsWidget
│   ├── TimerWidget
│   └── SettingsView
├── 🧠 Business Logic (Controllers)
│   ├── MusicController
│   └── LanguageController
├── 💾 Data Layer
│   ├── GetStorage (Local)
│   └── Audio Assets
├── 🌐 Services
│   ├── AdsService
│   └── AudioService
└── 🌍 Internationalization
    └── AppTranslations
```

---

## 🚀 Getting Started

### Prerequisites

- 📱 **Flutter SDK** `>=3.0.0`
- 🎯 **Dart SDK** `>=3.0.0`
- 📱 **Android Studio** / **VS Code**
- ☕ **Java 8+** (for Android)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sleep-sounds-app.git
   cd sleep-sounds-app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Add your audio files**
   ```bash
   # Add .mp3 files to:
   assets/audio/
   ```

4. **Configure AdMob** (Optional)
   ```dart
   // lib/services/ads_service.dart
   // Add your AdMob App ID and Ad Unit IDs
   ```

5. **Run the app**
   ```bash
   flutter run
   ```

### Building for Release

```bash
# Android (AAB for Play Store)
flutter build appbundle --release --no-tree-shake-icons

# Android (APK)
flutter build apk --release --no-tree-shake-icons

# iOS
flutter build ios --release
```

---

## 📁 Project Structure

```
lib/
├── 📱 main.dart                    # App entry point
├── 🎛️ controllers/
│   ├── music_controller.dart       # Music playback logic
│   └── language_controller.dart    # Language management
├── 📺 views/
│   ├── home_view.dart              # Main screen
│   ├── settings_view.dart          # Settings screen
│   └── widgets/                    # Reusable widgets
├── 🌐 translations/
│   └── app_translations.dart       # Multi-language support
├── 🎵 models/
│   └── music_model.dart            # Music data model
├── ⚙️ services/
│   └── ads_service.dart            # AdMob integration
└── 🔧 utils/
    └── constants.dart              # App constants
```

---

## 🌍 Languages

Our app supports **5 languages** with full localization:

| Language | Code | Status | Translator |
|----------|------|--------|-----------|
| 🇺🇸 English | `en_US` | ✅ Complete | Native |
| 🇧🇷 Português | `pt_BR` | ✅ Complete | Native |
| 🇪🇸 Español | `es_ES` | ✅ Complete | Community |
| 🇫🇷 Français | `fr_FR` | ✅ Complete | Community |
| 🇩🇪 Deutsch | `de_DE` | ✅ Complete | Community |

### Contributing Translations

Want to add a new language? We'd love your help!

1. Fork the repository
2. Add translations to `lib/translations/app_translations.dart`
3. Test the new language
4. Submit a pull request

---

## 📱 Download

<div align="center">

### Get Sleep Sounds App on your device

<a href="#"><img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Get it on Google Play" height="60"/></a>
<a href="#"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" alt="Download on the App Store" height="60"/></a>

*Coming soon to app stores*

</div>

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🐛 **Bug Reports**
- Use GitHub Issues
- Include device info
- Describe steps to reproduce

### ✨ **Feature Requests** 
- Check existing issues first
- Explain the use case
- Consider implementation impact

### 🔧 **Code Contributions**
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

### 📝 **Guidelines**
- Follow Dart/Flutter conventions
- Write descriptive commit messages
- Update documentation when needed
- Respect the existing code style

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Sleep Sounds App

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 🔒 Privacy

Your privacy is important to us. Our app:

- 🚫 **No personal data collection**
- 💾 **Local storage only**
- 🎯 **Anonymous ads**
- 🔒 **Secure by design**

Read our full [Privacy Policy](https://maurodev16.github.io/mussic-for-sleep-app-privacy-policy/)

---

## 📞 Support

Need help? We're here for you!

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mauro.developer.br@gmail.com)
[![GitHub Issues](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername/mussic-for-sleep-app/issues)

**Response time:** Within 48 hours  
**Languages:** English, Portuguese, Spanish, French, German

</div>

---

## 📊 Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/yourusername/sleep-sounds-app?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/sleep-sounds-app?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/sleep-sounds-app)
![GitHub license](https://img.shields.io/github/license/yourusername/sleep-sounds-app)

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/sleep-sounds-app)
![GitHub code size](https://img.shields.io/github/languages/code-size/yourusername/sleep-sounds-app)
![GitHub top language](https://img.shields.io/github/languages/top/yourusername/sleep-sounds-app)

</div>

---

## 🙏 Acknowledgments

Special thanks to:

- 🎵 **Audio Contributors** - For beautiful sleep sounds
- 🌍 **Translation Community** - For multi-language support  
- 🛠️ **Flutter Team** - For the amazing framework
- 📦 **GetX Community** - For state management
- 👥 **Beta Testers** - For valuable feedback

---

<div align="center">

### 💤 **Sweet dreams with Sleep Sounds** 🌙

*Built with ❤️ using Flutter*

**[⬆ Back to top](#-mussic-for-sleep-app)**

</div>
