# 🐱 Nyarm - Smart Alarm App

A smart alarm app with batch scheduling and a cute cat character.

![Nyarm Banner](assets/banner.png)

## ✨ Features

- **📅 Range Selection** - Select date ranges on calendar and set alarms at once
- **🚫 Exclusions** - Automatically exclude weekends or holidays
- **📋 Templates** - Save and reuse your favorite alarm settings
- **🐱 Cat Character** - Cute animated cat cheers you on!
- **🔔 Push Notifications** - Get notified right on time

## 📱 Installation

### Option 1: Download APK (Recommended)

1. Go to [Releases](../../releases) page
2. Download the latest `nyarm-vX.X.X.apk`
3. Install on your Android device

> ⚠️ You may need to enable "Install from unknown sources" on your device

### Option 2: Try with Expo Go

1. Install [Expo Go](https://expo.dev/client) on your phone
2. Clone this repository
3. Run `npm install`
4. Run `npx expo start`
5. Scan the QR code with Expo Go

## 🛠️ Development Setup

```bash
# Clone the repository
git clone https://github.com/imshota1009/nyarm-android.git
cd nyarm-android

# Install dependencies
npm install

# Start development server
npx expo start
```

## 📦 Building APK

### Local Build

```bash
# Install EAS CLI
npm install -g eas-cli

# Login to EAS
eas login

# Build development APK
eas build --platform android --profile development
```

### GitHub Actions

APK is automatically built when a new Release is created.

## 📁 Project Structure

```
nyarm-android/
├── App.tsx              # Main app
├── src/
│   ├── components/      # UI components
│   │   ├── Calendar.tsx
│   │   ├── CatCharacter.tsx
│   │   └── AlarmModal.tsx
│   ├── hooks/           # Custom hooks
│   │   ├── useAlarms.ts
│   │   ├── useTemplates.ts
│   │   └── useNotifications.ts
│   ├── utils/           # Utilities
│   │   ├── storage.ts
│   │   └── date.ts
│   └── types/           # Type definitions
│       └── index.ts
├── assets/              # Images
├── app.json             # Expo config
└── package.json
```

## 🎨 Tech Stack

- **Expo** (React Native)
- **TypeScript**
- **expo-notifications** - Push notifications
- **AsyncStorage** - Data persistence

## 📄 License

MIT License

---

🐱 *"Thanks for using Nyarm, nya~!"*
