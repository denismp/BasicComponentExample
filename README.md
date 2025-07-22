# BasicComponentExample

A minimal React Native project using [Expo](https://expo.dev/) to demonstrate basic components and layout in a mobile environment. Built with JavaScript and designed for quick startup and learning purposes.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) ≥ 16.x
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Expo Go](https://expo.dev/client) (optional for mobile testing)
- [Android Studio](https://developer.android.com/studio) or Xcode (optional for emulator testing)

### Install dependencies

```bash
npm install
```

### Start the project

```bash
npx expo start
```

Use the CLI options to:
- Open in iOS simulator (`i`)
- Open in Android emulator (`a`)
- Open in web browser (`w`)
- Scan QR code using Expo Go on your device

---

## 📁 Project Structure

```
BasicComponentExample/
├── App.js                 # Main application component
├── assets/               # Images and icons
│   ├── adaptive-icon.png
│   ├── favicon.png
│   ├── icon.png
│   └── splash-icon.png
├── app.json              # Expo configuration
├── index.js              # Entry point
├── package.json
└── README.md
```

---

## ✨ Features

- Basic usage of React Native components: `View`, `Text`, `StyleSheet`
- Expo-managed workflow for easy development and testing
- Cross-platform support: iOS, Android, Web

---

## 🛠 Troubleshooting

- **Missing assets/images folder**  
  If you encounter an error related to `assets/images`, create the folder:
  ```bash
  mkdir -p assets/images
  ```

- **No Android device found**  
  Follow [Expo’s Android setup guide](https://docs.expo.dev/workflow/android-studio-emulator) to use an emulator or USB device.

---

## 📚 Learn More

- [React Native Docs](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [Expo Router (optional)](https://expo.dev/router)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
