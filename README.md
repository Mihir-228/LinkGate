# My CareCrew

This is a **React Native** mobile application built with React Native version `0.75.2`. It provides a cross-platform mobile experience on both **iOS** and **Android**.

---

## Table of Contents

- [Getting Started](#getting-started)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Running the Application](#running-the-application)  
- [Folder Structure](#folder-structure)  
- [Dependencies](#dependencies)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Getting Started

Follow the instructions below to get a copy of the project up and running on your local machine for development and testing purposes.

---

## Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (Recommended: >= 16.x)  
- **npm** or **Yarn** (Latest version)  
- **Watchman** (For Mac users)  
- **Xcode** (For iOS development)  
- **Android Studio** (For Android development)  

---

## Installation

1. Clone the repository: We will provide the gitlab url to take a clone of it
2. Install dependencies:
npm install
# OR
yarn install
3. Install iOS dependencies (Mac users only):
cd ios && pod install
cd ..

## Running the Application

Start the server using following command: npx react-native start
Run iOS: npx react-native run-ios
Run Android: npx react-native run-android

## Folder Structure
project-root
│
├── android/            # Android native files
├── ios/                # iOS native files
├── App/                # Source files
│   ├── APIMANAGER/     # API Caling
│   ├── assets/         # Fonts and Images
│   ├── container/ 
│   │    ├── component/ # Reusable components
│   │    ├── navigator/ # Navigation setup
│   │    ├── screens/   # App screen
├── App.js              # Entry point
├── package.json      # Project metadata and dependencies
└── README.md         # Project documentation

## Dependencies
All dependancies are mentioned in the package.json

