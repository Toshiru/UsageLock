# Usage Lock 🔒

A Flutter application designed to help users monitor and control their device usage patterns. This app provides features for tracking app usage, setting time limits, and managing digital wellbeing.

## 📱 Features

- **App Usage Tracking**: Monitor how much time you spend on different applications
- **Usage Limits**: Set daily or weekly time limits for specific apps
- **Usage Statistics**: View detailed analytics of your app usage patterns
- **Notifications**: Get alerts when approaching or exceeding usage limits
- **Cross-Platform**: Available on Android and iOS devices

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (latest stable version)
- Android Studio / Xcode
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Toshiru/UsageLock.git
   cd UsageLock
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## 📋 Requirements

- **Android**: API level 21 or higher
- **iOS**: iOS 11.0 or higher
- **Permissions**: Usage access permissions for accurate tracking

## 🔧 Configuration

### Android Setup

1. Ensure you have the latest Android SDK installed
2. Enable developer options on your device
3. Grant usage access permissions in Settings > Apps > Special app access > Usage access

### iOS Setup

1. Ensure you have Xcode installed
2. Configure your Apple Developer account
3. Set up proper app permissions in Info.plist

## 📁 Project Structure

```
Usage Lock/
├── android/          # Android-specific files
├── ios/             # iOS-specific files
├── lib/             # Main Dart source code
│   └── utils/       # Utility functions and helpers
├── windows/         # Windows desktop support
├── linux/           # Linux desktop support
├── macos/           # macOS desktop support
└── build/           # Build outputs
```

## 🛠️ Development

### Building for Release

**Android:**
```bash
flutter build apk --release
```

**iOS:**
```bash
flutter build ios --release
```

### Running Tests

```bash
flutter test
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Toshiru**
- GitHub: [@Toshiru](https://github.com/Toshiru)

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- The open-source community for various packages and tools
- Users who provide feedback and suggestions

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/Toshiru/UsageLock/issues) page
2. Create a new issue with detailed information
3. Contact the maintainer

---

⭐ **Star this repository if you find it helpful!**
