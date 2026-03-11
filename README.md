# Innovation Bridge Platform 🌉

A digital ecosystem connecting **Innovators**, **Problem Owners**, and **Resource Providers**.
This platform functions as a **Supply Chain Management tool for Innovation**, prioritizing real-world demand (Problems) to drive meaningful supply (Ideas).

## 🏗 Project Structure

The project follows a **Feature-First, Clean Architecture** approach using Flutter & Riverpod.

**Folder Structure:**
- `lib/core`: Global configurations (Router, Theme, Constants).
- `lib/features`: Each feature (e.g., `problems_board`) contains:
  - `models/`: Data structures.
  - `repositories/`: Data fetching logic (Firestore).
  - `screens/`: UI pages.
- `lib/shared`: Reusable UI components.

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest stable)
- VS Code (recommended) or Android Studio

### Installation

1. **Install Dependencies:**
   Navigate to the app directory and install packages:
   ```bash
   cd innovation_bridge_app
   flutter pub get
   ```

2. **Run the App:**
   ```bash
   flutter run
   ```

## 🔑 Key Features (MVP)

- **Problem-First Board:** The landing page highlights urgent problems first.
- **Supply Chain Logic:** Matches Problems (Demand) -> Ideas (Supply) -> Resources (Logistics).
- **Hyper-Local Trust:** Verifiable profiles.

## 🛠 Tech Stack

- **Frontend:** Flutter (Mobile, Web)
- **State Management:** flutter_riverpod
- **Routing:** go_router
- **Backend:** Firebase (Auth, Firestore, Functions)


## 🔥 Firebase Setup

This project is pre-configured with a default Firebase Web credential for rapid local testing.

**For Web:**
Run directly: `flutter run -d chrome`

**For Mobile (Android/iOS):**
1. Ensure `google-services.json` (Android) or `GoogleService-Info.plist` (iOS) are present in their respective native directories.
2. OR run `flutterfire configure` to generate proper native credentials.
