# De-Crypto-Mobile

The Decrypto mobile app was created using React-native. Polished with an appealing color combination, modern design, clear code, easy to alter, and very simple to navigate for all users.

# Prerequisites

- XCode/Android Studio IDE

## OS

- MacOS(Required to prepare iOS project)
- Windows
- Ubuntu

## React Native CLI Quickstart

This app was created with React-native. All components required to construct a react-native project must be installed on your machine.

If you are new to React-native or do not have React-native installed on your machine, please follow the instructions outlined in this documentation's React Native CLI Quickstart [page](https://reactnative.dev/docs/environment-setup).

# Installation Guide

## 1. Open terminal and go to the root of downloaded project.

## 2. Link react native libs and assets

```bash
npx react-native-asset
```

## 3. Install node modules / libraries

```bash
yarn
```

### Pod install, For iOS only

```bash
cd ios && pod install && cd ..
```

## 4. Run the project

Go to the root folder in terminal and type command

### Android

```
npx react-native run-android
```

### iOS

```
npx react-native run-ios
```

# Android Configurations

Open the android project in Android Studio

## 1. Change the name of the app

Go to ```android -> app -> src -> main -> res -> values -> strings.xml``` and change the ```app_name``` key's value to the name of the app

## 2. Change the bundle id

Go to ```root folder -> android -> app -> build.gradle``` and change ```applicationId``` under ```defaultConfig```. Go to ```root folder -> android -> app -> main -> java``` and update the package name in ```MainActivity.java``` and ```MainApplication.java```

## 3. Change the splash screen

Go to ```root folder -> android -> app -> src -> main -> res -> drawable``` and update the ```background_splash.xml``` file and images as well.

Open ```root folder -> android -> app -> src -> main -> res -> layout``` and update the ```launch_screen.xml``` file

## 4. Change the app icon

Create an icon with a resolution of 1024x1024 pixels. After creating the icon open this [page](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=clipart&foreground.clipart=android&foreground.space.trim=1&foreground.space.pad=0.25&foreColor=rgba(96%2C%20125%2C%20139%2C%200)&backColor=rgb(68%2C%20138%2C%20255)&crop=0&backgroundShape=circle&effects=none&name=ic_launcher) and upload the icon. After making the necessary modifications, download the icons with ```ic_launcher``` (for square icon) and ```ic_launcher_round``` (for round icon) name. Replace the icons located in ```root folder -> android -> app -> src -> main -> res```

# iOS Configurations

Open the iOS project in XCode

## 1. Change the name of the app

Change the display name under the ```General``` tab

## 2. Change the bundle id

Change the bundle id under the ```General``` tab

## 3. Change the splash screen

Open ```LaunchScreen.xib``` and ```LoadingScreen.xib``` and change the image to your desired one

## 4. Change the app icon

Create an icon with a resolution of 1024x1024 pixels. After creating the icon open this [page](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=clipart&foreground.clipart=android&foreground.space.trim=1&foreground.space.pad=0.25&foreColor=rgba(96%2C%20125%2C%20139%2C%200)&backColor=rgb(68%2C%20138%2C%20255)&crop=0&backgroundShape=circle&effects=none&name=ic_launcher) and upload the icon. After making the necessary modifications, download the icons from there and replace them at ```root folder -> ios -> $APP_NAME -> Images.xcassets```

# Project Configuration

## 1. Change the logo

Go to ```src -> assets -> images``` and change the image named ```logo.png``` to your desired logo image

## 2. Change the app theme colors

Go to ```src -> theme -> Colors.ts```

## 3. Update the currency

Go to ```src -> config -> const.ts``` and update ```SelectCurrencyData```
 
