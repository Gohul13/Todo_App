# 🗓️ Planify - Your Smart Task Manager

Planify is a sleek and intuitive task management app built using **Flutter**, designed to help users stay productive and organized. Whether you're planning your day or tracking long-term goals, Planify makes it effortless.

---

## 📱 Features

- 📝 Create, update, and delete tasks
- ✅ Organize tasks by status: All / Completed / Pending
- 🔒 Secure Google Sign-In (Firebase Authentication)
- 🌗 Light and Dark mode support
- 📦 Task persistence using Hive (offline-first)
- 🧹 Swipe to delete with animation using `flutter_slidable`
- 🔄 Fully responsive UI
- 👤 User profile integration

---

## 🚀 Getting Started

### ✅ Prerequisites

- Flutter SDK (version 3.5.3 or higher)
- Android Studio / VS Code
- Firebase project configured with Google Sign-In

### 🔧 Installation

```bash
git clone https://github.com/your-username/planify.git
cd planify
flutter pub get
flutter pub run build_runner build
flutter run
```
### 📦 APK Download
      https://drive.google.com/file/d/1D4PhAoRIaBKtKx6ioXpFrdsfztPhZf1i/view?usp=drive_link

### 🛠️ Architecture
 - Planify follows MVVM architecture with Provider for state management, ensuring a clean separation of logic and UI.

### 🧩 Architecture Diagram
    <img width="1536" height="1024" alt="ChatGPT Image Jul 25, 2025, 03_20_26 PM" src="https://github.com/user-attachments/assets/17708c95-2f43-4f64-b75d-93bac68a6df5" />

### 🧠 Assumptions
 - App assumes users have internet access for Google login.

 - Currently supports Android only (iOS support can be added).

 - Tasks are stored locally using Hive; no remote sync yet.

 - Notifications and reminders were excluded from the MVP due to scope.

### 🎨 UI and Design
 - Built using Flutter with Material Design 3

 - Responsive design optimized for phones and tablets

 - Color palette supports both light and dark themes

 - Profile picture and user name dropdown in HomeScreen

 - Clean layout with smooth animations

### 🧰 Packages Used
 - Package	Purpose
 - provider	State management
 - firebase_auth	Firebase Authentication
 - google_sign_in	Google login
 - hive	Local task persistence
 - hive_flutter	Hive with Flutter integration
 - flutter_slidable	Swipe-to-delete animation
 - intl	Date formatting
 - lottie	Animated illustrations
 - google_fonts	Custom typography

### 🧪 Testing
 - Manual testing across dark/light modes

 - Firebase auth tested with multiple accounts

 - Task CRUD operations tested across screen sizes

### 🏁 Final Notes
 - Code is modular, readable, and scalable

 - UI is polished with transitions and proper layout structure

 - Easily extendable with new features (calendar, tags, reminders)

 - Tested and working debug APK available

 - MVVM + Provider pattern ensures maintainability
---
#This project is a part of a hackathon run by https://www.katomaran.com



