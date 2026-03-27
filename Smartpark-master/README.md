# 🅿️ SmartPark — Smart Parking System

A cross-platform **Flutter** application that streamlines parking slot reservations with real-time availability, digital tickets, and a seamless payment experience — all backed by **Firebase**.

## ✨ Features

- 🔐 **Authentication** — Google Sign-In & email/password login via Firebase Auth
- 🅿️ **Slot Booking** — Browse and reserve parking slots for today or tomorrow with date/time selection
- 🚗 **Vehicle Management** — Support for multiple vehicle types with number plate entry
- 💳 **Payment Flow** — Booking confirmation with animated success screen and ticket generation
- 🎫 **My Tickets** — View current and upcoming bookings tied to the logged-in user
- 🔔 **Alerts & Notifications** — In-app alert dialogs and audio feedback on key actions
- ☁️ **Real-time Database** — Slot availability and booking data synced live via Cloud Firestore & Firebase Realtime Database

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Flutter (Dart) |
| Auth | Firebase Authentication, Google Sign-In |
| Database | Cloud Firestore, Firebase Realtime Database |
| Storage | Firebase Storage |
| UI | Material Design, flutter_svg, page_transition, swipeable_button_view |
| Media | audioplayers / just_audio |

## 📱 Platform Support

Android · iOS · Linux · Windows

## 🚀 Getting Started
```bash
git clone https://github.com/your-username/smartpark.git
cd smartpark
flutter pub get
flutter run
```

> ⚠️ Requires a Firebase project. Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS), or configure `firebase_options.dart` using the FlutterFire CLI.

## 📁 Project Structure
```
lib/
├── main.dart          # App entry point & Firebase init
├── login.dart         # Authentication screen
├── mainparking.dart   # Core slot booking UI
├── parkAvail.dart     # Parking availability view
├── paymentP.dart      # Payment processing
├── paymentS.dart      # Payment success screen
├── showTickets.dart   # User's booking history
├── alertDialog.dart   # Reusable alert components
├── const.dart         # App-wide constants & theme
└── firebase_options.dart
```
