# BWStory React Native Application

## Blackcoffer React Native Developer Test Assignment

This project is developed as part of the React Native Developer Test Assignment provided by Blackcoffer.

The objective of the assignment is to implement two mobile application screens by referencing the BWStory application available on the Google Play Store.

### Implemented Screens

1. Discover Screen
2. Profile Screen

The application focuses on recreating the visual structure, layout, navigation elements, content presentation, and overall mobile user experience of the reference application.

---

## Project Objective

The primary objective of this project is to demonstrate the ability to:

- Develop mobile interfaces using React Native
- Create responsive and reusable UI components
- Reproduce a reference application's visual layout
- Implement mobile navigation
- Structure a React Native application professionally
- Test the application on an Android environment
- Generate an Android APK for deployment and evaluation

---

## Technology Stack

### Frontend

- React Native
- JavaScript
- React

### Development Environment

- Node.js
- npm
- Android Studio
- Android SDK
- Android Emulator
- Java Development Kit (JDK)

### Development Tools

- Visual Studio Code
- Android Studio
- Git
- GitHub

---

## Application Screens

### 1. Discover Screen

The Discover screen is designed to provide users with a feed-based experience for discovering news and community content.

The screen includes:

- Application header
- Search functionality UI
- News and content cards
- Images and content previews
- User information
- Follow interaction
- Content interaction elements
- Bottom navigation

The layout is designed to provide a clean and mobile-friendly browsing experience while following the visual structure of the BWStory reference application.

---

### 2. Profile Screen

The Profile screen provides a user-centric view containing profile information and user-generated content.

The screen includes:

- Profile header
- Profile picture
- User name
- Username
- Location
- User biography
- Edit Profile button
- Posts count
- Followers count
- Following count
- Posts, Saved and Liked sections
- User content cards
- Bottom navigation

The screen follows a clean card-based layout optimized for mobile devices.

---

## Application Structure

The project follows a standard React Native project structure.

```text
BWStory/
│
├── android/
│
├── ios/
│
├── src/
│   ├── components/
│   │   ├── BottomNavigation.js
│   │   ├── Header.js
│   │   └── PostCard.js
│   │
│   ├── screens/
│   │   ├── DiscoverScreen.js
│   │   └── ProfileScreen.js
│   │
│   └── navigation/
│       └── AppNavigation.js
│
├── App.js
├── package.json
├── package-lock.json
├── README.md
└── .gitignore
