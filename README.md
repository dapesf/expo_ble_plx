## Installation

```bash
npm install
npx patch-package
```

## Running the App

To start the app on Android, run:

```bash
npx expo run:android
```

To start the app on Iphone, run:

```bash
npx expo run:ios
```

## Android build

To compile and build the apk for Android, run:

```bash
cd ./android
./gradlew assembleRelease
adb install -r .\app\build\outputs\apk\release\app-release.apk
```

## IOS release