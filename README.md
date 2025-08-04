# Click-to-Buy
A Swift-based iOS app for browsing, configuring, and purchasing vehicles with Firebase authentication and SwiftUI.

#  Click to Buy 🚗

A SwiftUI-based iOS app for browsing, configuring, and purchasing   vehicles, integrated with Firebase for authentication and data storage. Supports English and Hindi localization, with features like vehicle comparison, favorites, and a user-friendly interface.

[![Swift](https://img.shields.io/badge/Swift-5.7-orange)](https://swift.org)
[![Platform](https://img.shields.io/badge/Platform-iOS%2016+-blue)](https://www.apple.com/ios)
[![Firebase](https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-yellow)](https://firebase.google.com)

## Features
- **Vehicle Browsing**: Explore   vehicles by type (SUV, Sedan, Hatchback, EV) with detailed specs and images.
- **Authentication**: Secure login/signup with Email, Google, and Apple Sign-In using Firebase Authentication.
- **Favorites & Comparison**: Save favorite vehicles and compare up to two vehicles side-by-side.
- **Localization**: Supports English and Hindi with `.strings` files for UI text.
- **Dynamic UI**: SwiftUI-powered interface with motion-based animations and dark/light mode support.
- **Purchase Flow**: Configure vehicles and initiate purchases, stored in Firestore.

## Project Structure
Click-To-Buy
├── App
│   ├── App.swift
│   ├── ContentView.swift
│   ├── DetailViews.swift
│   ├── LoginView.swift
│   ├── Managers.swift
│   ├── Models.swift
│   ├── AuthManager.swift
├── Resources/
│   ├── en.lproj/
│   │   ├── Localizable.strings
│   ├── hi.lproj/
│   │   ├── Localizable.strings
│   ├── profile_title.strings
├── README.md
├── .gitignore
├── LICENSE


## Screenshots
| Home Screen | Vehicle Details | Login Screen |
|-------------|-----------------|--------------|
| ![Home](  ) | ![Details]() | ![Login]() |

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/daksh541/Click-To-Buy.git
2. Open in Xcode: Open App.xcodeproj (not included in this repo; requires creating an Xcode project).
3. Install dependencies via CocoaPods or SPM:
Firebase (Auth, Firestore, Analytics)
GoogleSignIn

4. Configure Firebase:
Add GoogleService-Info.plist to the project (not included for security).
Update bundle ID and API keys in Xcode.

5. Build and run on iOS 16+.
   
## Usage

Browse Vehicles: Filter by type or search by name, engine, or specs.
Authenticate: Sign up or log in using email, Google, or Apple.
Favorites: Tap the heart icon to save vehicles.
Compare: Select up to two vehicles for side-by-side comparison.
Purchase: Configure a vehicle and submit purchase details.

## Dependencies

Firebase: Authentication, Firestore, Analytics
GoogleSignIn: Google Sign-In integration
SwiftUI: UI framework
CoreMotion: Device motion for animations

## Localization
Supports English (en.lproj) and Hindi (hi.lproj) for accessibility in the Indian market.
Contributing
Contributions are welcome! Please:

## Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit changes (git commit -m "Add YourFeature").
Push to the branch (git push origin feature/YourFeature).
Open a Pull Request.

## License
MIT License
Contact

GitHub: daksh541

Email: saidaksh.veluguri@gmail.com
