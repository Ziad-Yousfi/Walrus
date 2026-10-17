# Contributing to Walrus

Thank you for your interest in contributing to **Walrus**! We welcome bug reports, feature requests, code contributions, and translations.

---

## 🐛 Bug Reports & Feature Requests

Before creating a new report, please check the [existing issues](https://github.com/Ziad-Yousfi/Walrus/issues) to avoid duplicates.

- **Bug Reports**: When submitting a bug, please include:
  - Device model & Android OS version
  - Walrus app version and build variant (e.g. arm64-v8a)
  - Clear steps to reproduce the issue
  - URL of the media being tested (if applicable)
  - Relevant logs or stack traces
- **Feature Requests**: We welcome ideas for new tools, UI improvements, and workflow enhancements. Note that download-level platform support is governed by [yt-dlp](https://github.com/yt-dlp/yt-dlp).

Open a new report via [GitHub Issues](https://github.com/Ziad-Yousfi/Walrus/issues/new).

---

## 💻 Pull Requests & Code Contributions

1. **Discuss First**: For major changes or architectural additions, please open an issue first to discuss the implementation plan.
2. **Branching**:
   - Create your feature or bugfix branch off `main`: `git checkout -b feature/my-feature`
   - Open your Pull Request targeting the **`main`** branch.
3. **Commit Standards**:
   - Write clear, concise commit messages following standard conventions (e.g., `feat: ...`, `fix: ...`, `chore: ...`).
4. **Code Quality**:
   - Maintain idiomatic Kotlin and Jetpack Compose best practices.
   - Test your changes thoroughly on physical devices or emulators before submitting.

---

## 🛠️ Building From Source

### Requirements
- **JDK 17** or higher
- **Android Studio** Ladybug (or newer)
- **Android SDK** API 24 to API 37

### Build Commands
```bash
# Clone the repository
git clone https://github.com/Ziad-Yousfi/Walrus.git
cd Walrus

# Compile Kotlin & run checks
./gradlew compileGenericDebugKotlin

# Assemble Debug APK
./gradlew assembleGenericDebug

# Assemble Release APK
./gradlew assembleGenericRelease
```

---

## 🌍 Translations

Walrus supports many languages thanks to the global open-source community. If you would like to help translate Walrus into your language, feel free to submit PRs modifying the corresponding `app/src/main/res/values-*/strings.xml` or documentation files in `translations/`.
