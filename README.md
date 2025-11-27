# 🎨 AnimationMaster - React Native Animation Tutorial App

[![React Native](https://img.shields.io/badge/React%20Native-0.73-blue.svg)](https://reactnative.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> **A comprehensive React Native educational app demonstrating professional animation patterns, navigation architectures, and TypeScript best practices.**

Perfect for developers learning React Native animations, gesture handling, and modern app architecture patterns.

---

## ✨ Features

### 🧭 **Complete Navigation System**
- ✅ **Drawer Navigation** - Custom drawer with theme integration
- ✅ **Bottom Tabs** - 5 animated tabs with badges
- ✅ **Stack Navigation** - Custom screen transitions
- ✅ **Deep Linking** - URL-based navigation support

### 🎭 **15+ Animation Patterns**
- **Fade Animations** - Smooth opacity transitions
- **Slide Animations** - Position-based movements  
- **Spring Physics** - Natural bounce effects
- **Scale Animations** - Size transformations
- **Rotation Animations** - 360° transforms
- **Stagger Animations** - Sequential list items
- **Parallel Animations** - Multiple simultaneous effects
- **Sequence Animations** - Ordered animation chains
- **Loop Animations** - Infinite repeating effects
- **Decay Animations** - Momentum-based fling gestures

### 👆 **Gesture Handling (PanResponder)**
- Drag & Drop with setOffset
- Swipe Detection (left/right threshold)
- Multi-touch Pinch to Zoom
- Rotation Gestures
- Velocity-based Decay
- Touch feedback animations

### 🌗 **Dynamic Theming**
- System-aware dark/light mode
- Manual theme switching
- Persistent theme storage (AsyncStorage)
- React Navigation theme sync
- Custom color system

### 📱 **Production-Ready Screens**
1. **HomeScreen** - Fade + Slide entrance animations
2. **ProfileScreen** - Spring + Scale interactions
3. **GalleryScreen** - FlatList stagger animations
4. **ExploreScreen** - Swipeable cards with PanResponder
5. **NotificationsScreen** - Pulse animations + badges
6. **SettingsScreen** - Theme controls
7. **AnimationShowcaseScreen** - All patterns demo
8. **DetailScreen** - Custom transitions

---

## 🚀 Quick Start

### Prerequisites
- Node.js >= 18
- React Native CLI
- Android Studio / Xcode
- TypeScript knowledge (recommended)

### Installation

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

## Step 1: Start Metro

First, you will need to run **Metro**, the JavaScript build tool for React Native.

To start the Metro dev server, run the following command from the root of your React Native project:

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Build and run your app

With Metro running, open a new terminal window/pane from the root of your React Native project, and use one of the following commands to build and run your Android or iOS app:

### Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

### iOS

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
bundle exec pod install
```

For more information, please visit [CocoaPods Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up correctly, you should see your new app running in the Android Emulator, iOS Simulator, or your connected device.

This is one way to run your app — you can also build it directly from Android Studio or Xcode.

## Step 3: Modify your app

Now that you have successfully run the app, let's make changes!

Open `App.tsx` in your text editor of choice and make some changes. When you save, your app will automatically update and reflect these changes — this is powered by [Fast Refresh](https://reactnative.dev/docs/fast-refresh).

When you want to forcefully reload, for example to reset the state of your app, you can perform a full reload:

- **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Dev Menu**, accessed via <kbd>Ctrl</kbd> + <kbd>M</kbd> (Windows/Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (macOS).
- **iOS**: Press <kbd>R</kbd> in iOS Simulator.

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [docs](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you're having issues getting the above steps to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.


