# Firebase Chat Android Application

A proof of concept Android chat application built with Firebase, demonstrating real-time messaging capabilities.

## Features

- Real-time messaging using Firebase Realtime Database
- User authentication
- Modern Material Design UI
- Support for Android API level 16 and above

## Prerequisites

- Android Studio 3.0 or higher
- JDK 8 or higher
- Firebase account and project setup
- Android device or emulator running Android 4.1 (API level 16) or higher

## Setup

1. Clone the repository:
```bash
git clone https://github.com/ramyhelow/Firebase-Chat-App-PoC.git
```

2. Open the project in Android Studio

3. Set up Firebase:
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com)
   - Add your Android app to the Firebase project
   - Download the `google-services.json` file and place it in the `app` directory
   - Enable Authentication and Realtime Database in Firebase Console

4. Build and run the application

## Project Structure

```
app/
├── src/
│   └── main/
│       ├── java/com/ramyhelow/chatapp/
│       │   └── MainActivity.java
│       ├── res/
│       └── AndroidManifest.xml
├── build.gradle
└── google-services.json
```

## Dependencies

- AndroidX AppCompat
- Material Design Components
- Firebase Authentication
- Firebase Realtime Database
- AndroidX ConstraintLayout

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request