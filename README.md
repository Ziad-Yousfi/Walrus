<div align="center">

<img src="fastlane/metadata/android/en-US/images/icon.png" width="160" height="160" alt="Walrus Logo" align="center">

# Walrus

### 🎬 Advanced Video & Audio Downloader for Android

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/Ziad-Yousfi/Walrus?color=black&label=Latest%20Release&logo=github)](https://github.com/Ziad-Yousfi/Walrus/releases/latest/)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Ziad-Yousfi/Walrus?include_prereleases&label=Preview&logo=Github)](https://github.com/Ziad-Yousfi/Walrus/releases/)
[![Changelog](https://img.shields.io/badge/Changelog-lightgray?style=flat&color=gray&logo=keep-a-changelog)](CHANGELOG.md)
[![GitHub all releases](https://img.shields.io/github/downloads/Ziad-Yousfi/Walrus/total?label=Downloads&logo=github)](https://github.com/Ziad-Yousfi/Walrus/releases/)
[![GitHub Repo stars](https://img.shields.io/github/stars/Ziad-Yousfi/Walrus?style=flat&logo=github&color=f8e444)](https://github.com/Ziad-Yousfi/Walrus/stargazers)
[![Supported-Sites](https://img.shields.io/badge/1000%2B%20Sites-9cf?style=flat&label=Supported)](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md)
[![Android API](https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=flat)](https://developer.android.com/about/versions/nougat)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

**Walrus** is a modern, privacy-focused video and audio downloader for Android powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp). Built with Jetpack Compose and Material 3, it offers high-speed downloads, an exclusive Gradient Dark theme, batch downloading, an app lock, and extensive audio extraction options.

Maintained and actively developed by **[fernstack](https://github.com/Ziad-Yousfi)**.

---

### 🌍 Language Support

[English](README.md)
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-zh_Hans.md">简体中文</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-zh_Hant.md">繁體中文</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-ar.md">العربية</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-pt.md">Português</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-ua.md">Українська</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-th.md">ภาษาไทย</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-fa.md">فارسی</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-it.md">Italiano</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-ja.md">日本語</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-hi.md">हिंदी</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-bn.md">বাংলা</a>
&nbsp;&nbsp;|&nbsp;&nbsp;
<a href="translations/README-ru.md">Русский</a>

</div>

---

## 📱 Screenshots

<div align="center">
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.jpg" width="30%" alt="Home Screen" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.jpg" width="30%" alt="Download Configuration" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.jpg" width="30%" alt="Format Selection" />
  <br><br>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.jpg" width="30%" alt="Download Manager" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/5.jpg" width="30%" alt="Swipeable Details" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/6.jpg" width="30%" alt="Tools Hub" />
  <br><br>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/7.jpg" width="30%" alt="Settings" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/8.jpg" width="30%" alt="Look & Feel" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/9.jpg" width="30%" alt="About Page" />
</div>

---

## ✨ Features

### 🎨 Modern UI & Theming
- **Exclusive Gradient Dark Theme**: Deep OLED black backgrounds (#0A0A0F, #14141F) paired with subtle violet and blue linear gradients and glassmorphism cards.
- **Material You Dynamic Color**: Automatically harmonizes with your system wallpaper palette on Android 12+.
- **Fluid Micro-Animations**: Smooth screen transitions and reactive state feedback.
- **Biometric Security / App Lock**: Protect your downloads and history with fingerprint or face authentication.

### 🚀 Powerful Download Capabilities
- **Universal Downloader**: Works with 1000+ platforms via [yt-dlp](https://github.com/yt-dlp/yt-dlp) (YouTube, TikTok, Instagram, Twitter/X, Reddit, Twitch, Facebook, SoundCloud, Vimeo, and many more).
- **High-Speed Downloads**: Integrated [aria2c](https://github.com/aria2/aria2) multi-threaded accelerator with automatic retries and resume support.
- **Audio Extraction**: Save files as MP3, M4A, OPUS, FLAC, or WAV with embedded metadata and album artwork using [mutagen](https://github.com/quodlibet/mutagen).
- **Subtitles Support**: Download subtitles as separate files (.srt, .vtt) or embed them directly into the video container.
- **Playlists & Batch Downloads**: Download entire playlists or paste multiple links at once.

### 🧰 Dedicated Tool Suite ("More Tools")
- **Batch URL Importer**: Paste and queue multiple custom video/audio links simultaneously.
- **Thumbnail Downloader**: Extract high-resolution video thumbnails with format conversion (PNG / WebP / JPG).
- **Video Info Downloader**: Export comprehensive video metadata (title, description, tags, view count) in clean `.txt` or `.json` format.
- **Comment Extractor**: Download YouTube video comment sections for offline reading and analysis.
- **Custom Commands**: Create, save, and execute custom yt-dlp command-line templates directly in the app.

### 🔒 Privacy & Local Processing
- **100% Free and Open Source**: Licensed under GPL-3.0.
- **No Account Required**: No telemetry, tracking, or personal data collection.
- **Seamless In-App Updates**: Built-in update checker pointing directly to official GitHub releases.

---

## ⬇️ Download & Installation

### 📦 Latest Stable Release

Download the APK matching your device from [GitHub Releases](https://github.com/Ziad-Yousfi/Walrus/releases/latest):

| Architecture | Recommended Devices |
|--------------|---------------------|
| **arm64-v8a** | **Recommended** for almost all modern Android phones & tablets (64-bit ARM) |
| **armeabi-v7a** | Older Android devices (32-bit ARM) |
| **x86_64** | Intel / AMD 64-bit devices, Chromebooks, and Android emulators |
| **x86** | Older 32-bit x86 devices |
| **universal** | Compatible with all devices (larger package size) |

### 📱 Device Compatibility

| Requirement | Specification |
|-------------|---------------|
| **Minimum Android** | Android 7.0 (API 24) |
| **Target Android** | Android 17 (API 37) |
| **Current Version** | v3.1.0 |

### 🛠️ Installation Steps

1. Download the suitable `.apk` from [Releases](https://github.com/Ziad-Yousfi/Walrus/releases/latest).
2. Open the downloaded file and allow installation from your browser/file manager if prompted.
3. Launch **Walrus** and grant notification & storage permissions to enable background downloads.

---

## ❓ Frequently Asked Questions

<details>
<summary><b>🎨 How do I enable the Gradient Dark theme?</b></summary>
<br>
Go to <b>Settings → Display → Dark theme</b>, turn on Dark Theme, and toggle <b>Gradient Dark</b>.
</details>

<details>
<summary><b>🔄 How do automatic updates work?</b></summary>
<br>
Walrus checks the official GitHub repository releases on startup. When an update is detected, an in-app prompt displays the changelog and lets you download and install the update with a single tap. You can toggle this setting in <b>Settings → About → Auto update</b>.
</details>

<details>
<summary><b>🎵 How can I download only the audio?</b></summary>
<br>
When pasting a link or using the quick download prompt, switch the toggle to <b>Save as audio</b>. You can choose your preferred audio format (MP3, M4A, OPUS, FLAC, WAV) and quality settings in download configuration.
</details>

<details>
<summary><b>🛡️ Is Walrus safe? Does it collect any data?</b></summary>
<br>
Yes, 100%. Walrus is completely open-source and free of trackers, telemetry, analytics, and advertisements. All processing, downloads, and conversions occur entirely locally on your device.
</details>

<details>
<summary><b>🏷️ What is the origin of Walrus?</b></summary>
<br>
Walrus is an enhanced fork of the open-source downloader family: originally created as <i>Seal</i> by JunkFood02, extended with UI and feature updates by Mahesh Technicals (<i>Sealplus</i>), and now maintained and evolved by <b>fernstack</b> under the project name <b>Walrus</b>.
</details>

<details>
<summary><b>⚠️ What should I do if a download fails?</b></summary>
<br>
1. Go to <b>Settings → About</b> and tap <b>Update yt-dlp</b> to ensure you have the latest extraction scripts.<br>
2. Check if the website requires cookies/login (you can export cookies in Settings).<br>
3. Check the <a href="https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md">yt-dlp supported sites list</a> or report an issue on our <a href="https://github.com/Ziad-Yousfi/Walrus/issues">Issue Tracker</a>.
</details>

---

## 🏗️ Technology Stack

| Component | Technology | Version |
|-----------|------------|---------|
| **Language** | Kotlin (K2 Compiler) | 2.3.21 |
| **UI Framework** | Jetpack Compose (Material 3) | BOM 2026.05.01 |
| **Engine** | yt-dlp via youtubedl-android | 2025.12.08 |
| **Accelerator** | aria2c | Embedded native binary |
| **Metadata** | mutagen | Python package |
| **Database** | Room | 2.8.4 |
| **Image Loading** | Coil 3 | 3.4.0 |
| **Build System** | Gradle (KTS) | 9.5.1 |
| **Min / Target SDK** | Android 7.0 / Android 17 | API 24 / API 37 |

---

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome!

1. **Bug Reports & Ideas**: Open an issue on [GitHub Issues](https://github.com/Ziad-Yousfi/Walrus/issues).
2. **Code Contributions**:
   - Fork the repository.
   - Create your feature branch (`git checkout -b feature/my-feature`).
   - Commit your changes with clear messages (`git commit -m "feat: add my feature"`).
   - Push to your branch and open a Pull Request targeting the `main` branch.
3. **Building Locally**:
   ```bash
   # Clone the repository
   git clone https://github.com/Ziad-Yousfi/Walrus.git
   cd Walrus

   # Build debug APK
   ./gradlew assembleGenericDebug

   # Build release APK
   ./gradlew assembleGenericRelease
   ```

For detailed guidelines, please refer to [CONTRIBUTING.md](CONTRIBUTING.md).

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/chart?repos=Ziad-Yousfi/Walrus&type=Date)](https://www.star-history.com/#Ziad-Yousfi/Walrus&Date)

---

## 🙏 Credits & Acknowledgments

Walrus is built upon the wonderful contributions of the open-source community:

- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — The core video downloading engine.
- **[youtubedl-android](https://github.com/yausername/youtubedl-android)** — Android port & JNI bindings for yt-dlp.
- **[aria2](https://github.com/aria2/aria2)** — Multi-connection download utility.
- **[mutagen](https://github.com/quodlibet/mutagen)** — Audio tag and metadata editor.
- **[JunkFood02](https://github.com/JunkFood02)** — Creator of the original [Seal](https://github.com/JunkFood02/Seal) application.
- **[Mahesh Technicals](https://github.com/MaheshTechnicals)** — Developer of the [Sealplus](https://github.com/MaheshTechnicals/Sealplus) fork and initial theme enhancements.
- **[fernstack](https://github.com/Ziad-Yousfi)** — Maintainer of the **Walrus** project.
- **Weblate Translators & Community** — For internationalization and user feedback.

---

## 📃 License

Distributed under the **GNU General Public License v3.0 (GPL-3.0)**. See [LICENSE](LICENSE) for more information.

> [!NOTE]
> In accordance with the original creator's trademark disclaimer, derivatives and forks should not use the original "Seal" trademark in their application branding. This project is independently named and distributed as **Walrus**.

<div align="right">
  <a href="#top">👆 Back to top</a>
</div>
