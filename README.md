# Spirit-Realm-Centre-Inc
Memembership Management System

# Spirit Realm Centre Mobile App (Cordova)

This project contains a Cordova-based mobile package for the Spirit Realm Centre Management System.

## How to Build the Android APK

### 1. Prerequisites
- Node.js and npm installed: https://nodejs.org/
- Cordova installed globally:
  ```
  npm install -g cordova
  ```
- Android Studio installed (includes Android SDK): https://developer.android.com/studio
- Set the ANDROID_HOME environment variable to your SDK path (e.g., `C:\Users\YourName\AppData\Local\Android\Sdk`)

### 2. Clone the Repository
```
git clone https://github.com/MortalFiles-Memorial-Platform/Spirit-Realm-Centre-Inc.git
cd Spirit-Realm-Centre-Inc/src-mobile
```

### 3. Build the APK
```
npx cordova build android
```

- The APK will be generated at:
  ```
  platforms/android/app/build/outputs/apk/debug/app-debug.apk
  ```

### 4. Distribute the APK
- Upload the APK to Google Drive, Dropbox, or any file host.
- Share the download link for users to install on Android devices.

## Notes
- This APK is unsigned (debug). For production, sign the APK before publishing to the Play Store.
- For iOS builds, a Mac and Xcode are required.

---
For any issues, please open an issue on the repository or contact the maintainer.
