# AI Fitness App

A modern Flutter application for AI-powered fitness training with a beautiful and intuitive user interface.

## TODO List

### Firebase Integration Tasks
1. Authentication Implementation
   - [ ] Set up Firebase Authentication
   - [ ] Implement email/password sign-in
   - [ ] Add social authentication (Google, Facebook)
   - [ ] Create user profile management
   - [ ] Implement password reset flow
   - [ ] Add email verification

2. Cloud Firestore Implementation
   - [ ] Design database structure
   - [ ] Create user profile collection
   - [ ] Set up workout plans collection
   - [ ] Implement exercise tracking
   - [ ] Add progress tracking
   - [ ] Set up data validation rules

3. Firebase Storage Implementation
   - [ ] Set up storage structure
   - [ ] Implement profile picture upload
   - [ ] Add workout video storage
   - [ ] Create progress photo storage
   - [ ] Implement file management
   - [ ] Set up storage security rules

## Features

### Authentication
- Onboarding screens with smooth animations
- Modern login screen with email and password validation
- Comprehensive registration form with:
  - First name and last name
  - Email validation
  - Password with visibility toggle
  - Date of birth picker
  - Form validation feedback
- Loading states and animations
- Error handling and user feedback


## Getting Started

### Prerequisites

- Flutter SDK
- iOS: Xcode (for iOS development)
- Android: Android Studio (for Android development)
- VS Code or any preferred IDE

### Installation

1. Clone the repository
2. Navigate to project directory:
   ```bash
   cd hello_world
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```

### Running the Application

#### Check Available Devices

1. List all connected devices:
   ```bash
   flutter devices
   ```
   This will show all available devices including:
   - Physical devices (iOS/Android phones)
   - Simulators/Emulators
   - Web browsers
   - Desktop platforms

2. Start specific emulators (optional):
   ```bash
   flutter emulators             # List available emulators
   flutter emulators --launch <emulator-id>  # Launch specific emulator
   ```

#### Run the Application

1. Run on default device:
   ```bash
   flutter run
   ```

2. Run on specific device:
   ```bash
   flutter run -d <device-id>    # Run on specific device
   flutter run -d chrome         # Run in Chrome browser
   flutter run -d macos          # Run on macOS
   ```

### Running on iOS Device

1. Connect your iOS device via USB
2. Trust your computer on the iOS device
3. Install CocoaPods dependencies:
   ```bash
   cd ios
   pod install
   ```
4. Open Xcode and set up signing:
   ```bash
   open Runner.xcworkspace
   ```
   - Select the Runner project
   - Choose your team in Signing & Capabilities
   - Update Bundle Identifier if needed

5. Run the application:
   ```bash
   flutter run
   ```

### Development Resources

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Online documentation](https://docs.flutter.dev/)
- [Firebase Flutter documentation](https://firebase.google.com/docs/flutter/setup)

## Project Structure

```
lib/
├── screens/
│   ├── onboarding_screen.dart   # Initial app screens with welcome message
│   ├── login_screen.dart        # User login functionality
│   ├── register_screen.dart     # New user registration
│   └── welcome_screen.dart      # Post-authentication welcome screen
├── main.dart                    # App entry point and configuration
└── firebase_options.dart        # Firebase configuration
```

## Troubleshooting

### Common Issues

1. Device not detected:
   - Check USB connection
   - Trust computer on device
   - Run `flutter doctor` for diagnostics

2. iOS build fails:
   - Verify Xcode installation
   - Check signing certificates
   - Run `pod install` in ios directory

3. Hot Reload not working:
   - Press 'r' in terminal
   - Restart app with 'R'
   - Check debug console for errors

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
