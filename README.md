# Hanzi Reader - Android App

Android mobile application for Hanzi Reader.

## Features

- 📖 Chinese text reading and annotation
- 🔤 Pinyin and tone marks display
- 🌈 Color-coded HSK levels
- 💾 Offline dictionary and data
- 📊 Vocabulary tracking
- 🔊 Text-to-speech
- 🎯 HSK practice lists

## Tech Stack

- **Kotlin** - Language
- **Jetpack Compose** - UI framework
- **Room** - Local database
- **Retrofit** - HTTP client
- **HanLP** - Chinese NLP
- **TTS** - Text-to-speech

## Project Structure

```
app/src/main/
├── java/com/hanzi/reader/
│   ├── ui/
│   ├── viewmodel/
│   ├── repository/
│   ├── database/
│   ├── service/
│   └── MainActivity.kt
└── res/
```

## Building & Running

### Prerequisites
- Android Studio 2022.1+
- Android SDK 24+
- Kotlin 1.8+

### Development

```bash
# Build and run on emulator
./gradlew installDebug

# Run tests
./gradlew test
```

### Release Build

```bash
./gradlew bundleRelease
```

## Related Repositories

- [Backend API](https://github.com/FrancescaWiegman/hanzi-reader-api)
- [Web Frontend](https://github.com/FrancescaWiegman/hanzi-reader-web)
- [Data Pipeline](https://github.com/FrancescaWiegman/hanzi-reader-data-pipeline)
- [iOS](https://github.com/FrancescaWiegman/hanzi-reader-ios)
