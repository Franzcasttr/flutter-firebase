# ExploreJobs Flutter

A job searching mobile application built with Flutter, featuring Firebase Authentication and Cloud Firestore integration.

## Features

- User authentication (Email/Password)

## Tech Stack

- Flutter
- Firebase Authentication
- Cloud Firestore
- Firebase Storage

## Prerequisites

- Flutter SDK (3.0.0 or higher)
- Firebase project
- Xcode / VS Code

## Setup

1. **Clone Repository**

   ```bash
   git clone https://github.com/yourusername/explorejobs
   cd explorejobs
   ```

2. **Firebase Configuration**

   - Create Firebase project
   - Enable Authentication methods
   - Configure Cloud Firestore
   - Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)
   - Place configuration files in:
     - Android: `android/app/google-services.json`
     - iOS: `ios/Runner/GoogleService-Info.plist`

3. **Install Dependencies**

   ```bash
   flutter pub get
   ```

4. **Run Application**
   ```bash
   flutter run
   ```

## Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Cloud Firestore](https://firebase.google.com/docs/firestore)
