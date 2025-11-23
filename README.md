# React Native Notes App

Aplikasi Notes berbasis React Native yang dibangun menggunakan Expo Router dengan TypeScript. Project ini menyediakan template modern untuk pengembangan aplikasi mobile cross-platform.

## 🚀 Tech Stack

- **React Native** 0.81.5
- **React** 19.1.0
- **Expo** ~54.0.23
- **Expo Router** ~6.0.14
- **TypeScript** ~5.9.2
- **React Navigation** (Bottom Tabs & Native)

## 📋 Prerequisites

Sebelum memulai, pastikan Anda telah menginstall:

- Node.js (versi LTS terbaru)
- npm atau yarn
- Expo CLI
- iOS Simulator (untuk Mac) atau Android Emulator

## 🔧 Installation

1. Clone repository ini:
```bash
git clone https://github.com/kevinmf1/react-native-notes-app.git
cd react-native-notes-app
```

2. Install dependencies:
```bash
npm install
```

## 🏃 Running the App

### Start Development Server
```bash
npm start
```

### Platform Specific

**Android:**
```bash
npm run android
```

**iOS:**
```bash
npm run ios
```

**Web:**
```bash
npm run web
```

## 📁 Project Structure

```
react-native-notes-app/
├── app/                    # Expo Router pages
│   ├── (tabs)/            # Tab navigation screens
│   ├── _layout.tsx        # Root layout
│   └── modal.tsx          # Modal screen
├── components/            # Reusable components
│   ├── ui/               # UI components
│   ├── external-link.tsx
│   ├── haptic-tab.tsx
│   ├── hello-wave.tsx
│   ├── parallax-scroll-view.tsx
│   ├── themed-text.tsx
│   └── themed-view.tsx
├── constants/            # App constants
├── hooks/               # Custom React hooks
├── assets/              # Images, fonts, etc.
├── scripts/             # Utility scripts
└── package.json
```

## 🛠️ Available Scripts

- `npm start` - Start Expo development server
- `npm run android` - Run on Android device/emulator
- `npm run ios` - Run on iOS simulator
- `npm run web` - Run on web browser
- `npm run lint` - Run ESLint
- `npm run reset-project` - Reset project to initial state

## 📦 Key Dependencies

### Core
- `expo` - Expo SDK
- `expo-router` - File-based routing
- `react-native-reanimated` - Animations
- `react-native-gesture-handler` - Gesture handling
- `react-native-safe-area-context` - Safe area support

### UI & Navigation
- `@react-navigation/bottom-tabs` - Bottom tab navigation
- `@react-navigation/native` - React Navigation core
- `@expo/vector-icons` - Icon library
- `expo-symbols` - SF Symbols support

### Development
- `typescript` - TypeScript support
- `eslint` - Code linting
- `eslint-config-expo` - Expo ESLint configuration

## 🎨 Features

- ✅ File-based routing with Expo Router
- ✅ TypeScript support
- ✅ Bottom tab navigation
- ✅ Modal screens
- ✅ Themed components (light/dark mode ready)
- ✅ Haptic feedback
- ✅ Animated components
- ✅ Parallax scroll view
- ✅ Safe area handling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is private and not licensed for public use.

## 👤 Author

**kevinmf1**
- GitHub: [@kevinmf1](https://github.com/kevinmf1)

## 📞 Support

Jika Anda menemukan bug atau memiliki pertanyaan, silakan buka [issue](https://github.com/kevinmf1/react-native-notes-app/issues).

---

**Note:** Project ini dibuat menggunakan Expo. Untuk informasi lebih lanjut tentang Expo, kunjungi [dokumentasi Expo](https://docs.expo.dev/).
