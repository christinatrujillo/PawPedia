# 🐾 Animal App

An educational iOS app built with SwiftUI and Firebase, designed for young children to explore animals, listen to animal sounds, and discover related information.

---

## 📱 App Overview

Animal App makes learning about animals fun and accessible for kids. Each animal has its own dedicated page with information, sounds, and links to further reading — all wrapped in a clean, child-friendly interface.

---

## ✨ Features

- **Animal Exploration** — Browse a collection of animals with dedicated detail pages
- **Animal Sounds** — Tap to hear each animal's sound
- **Wikipedia Integration** — Links to related animal content for curious kids
- **User Authentication** — Secure login via Firebase Authentication
- **Personalized Experience** — Firebase real-time database stores user data for a customized experience
- **Child-Friendly UI** — Intuitive navigation and engaging visuals designed for young users

---

## 🛠️ Tech Stack

- **Language:** Swift
- **Framework:** SwiftUI
- **IDE:** Xcode
- **Backend:** Firebase (Authentication + Realtime Database)
- **Architecture:** OOP — separated UI, business logic, and data handling

---

## 📁 Project Structure
```
AnimalApp/
├── AnimalApp.xcodeproj/    # Xcode project files
├── AnimalApp/
│   ├── Animal.swift        # Animal data model
│   ├── AnimalAppApp.swift  # App entry point
│   ├── ContentView.swift   # Main view
│   ├── DetailView.swift    # Individual animal detail page
│   ├── Sound.swift         # Audio playback logic
│   ├── Assets.xcassets/    # Images and app icons
│   └── Sounds/             # Animal sound files
```

---

## ⚙️ Installation & Setup

### Prerequisites
- Xcode 13+
- iOS 15+
- A Firebase project with Authentication and Realtime Database enabled

### Setup
1. Clone the repository
```bash
git clone https://github.com/christinatrujillo/AnimalApp.git
```
2. Open `AnimalApp.xcodeproj` in Xcode
3. Add your `GoogleService-Info.plist` from your Firebase project to the root of the app
4. Build and run on a simulator or device

---

## 👩‍💻 Author

**Christina Trujillo** — [GitHub](https://github.com/christinatrujillo)
