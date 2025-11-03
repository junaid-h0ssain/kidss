
# kidss

A small Flutter app demonstrating local data persistence using Hive.


## How to start
1. Install Flutter and set up your environment: https://docs.flutter.dev/get-started/install
2. From the project root, fetch packages:
3. Alternatively use VScode Flutter extension for auto-install and setup (it's quite easier this way)
4. Also try [DartPad](https://dartpad.dev/) online (i have not tried it)

Clone and run

```bash
git clone <this-repo-url>
cd booktracker2

flutter pub get

flutter run
```

To run on a specific device:

```bash
flutter devices

flutter run -d <device-id>
```

Build release APK (Android)

```bash
flutter build apk --release
```

Build for iOS (requires macOS + Xcode)

```bash
flutter build ios --release
```

Build for web

```bash
flutter build web
```

## Troubleshooting

- You need to have [AndroidStudion](https://developer.android.com/studio) already set-up
- New versions of AndroidStudio may cause trouble while running (i don't know why) 
- In that case try the [archive](https://developer.android.com/studio/archive)


