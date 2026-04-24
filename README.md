# React Navigation Contact App

This is a React Native Expo app demonstrating navigation with React Navigation. It features a bottom tab navigator with Home and Settings tabs, where the Home tab contains a stack navigator with Home and Detail screens.

## Getting Started

### Prerequisites

- Node.js
- Expo CLI (`npm install -g @expo/cli`)

### Installation

1. Install dependencies:
   ```
   npm install
   ```

### Running the App

1. Start the Expo development server:
   ```
   npm start
   ```

2. Use the Expo Go app on your device or an emulator to scan the QR code and run the app.

## Project Structure

- `App.js`: Main app component with navigation setup
- `screens/`: Contains screen components
  - `HomeScreen.js`: Home screen with navigation to details
  - `DetailScreen.js`: Detail screen
  - `SettingsScreen.js`: Settings screen

## Navigation

- Bottom Tab Navigator: HomeTab and Settings
- Stack Navigator in HomeTab: Home -> Detail

## Dependencies

- React Navigation
- Expo Vector Icons