<h1 align="center">🍽️ React Native Recipe App 🍽️</h1>


<p align="center">A delightful mobile application for discovering and saving your favorite recipes! 🎉</p>

## ✨ Key Features

- 🔐 **Authentication System** - Secure registration, login, and 6-digit email verification powered by **Clerk** 🔒
- 🍳 **Recipe Discovery** - Explore featured dishes and filter by various meal categories 🎯
- 🔍 **Smart Search** - Find recipes and view comprehensive cooking instructions 📖
- 🎥 **Video Guides** - Recipe pages feature embedded YouTube video tutorials 🎬
- ❤️ **Favorites Collection** - Save your preferred recipes and access them from a dedicated favorites section 💾
- ⚡ **Modern Tech Stack** - Built with React Native, Express, PostgreSQL, and Expo 🚀
- 🌈 **Theming Support** - Choose from 8 beautiful color themes 🎨
- 🆓 **Completely Free** - No paid services required - 100% free tools and resources 💰

---

## 🛠️ Environment Configuration

### Backend Setup (`/backend`)

Create a `.env` file in the backend directory with the following variables:

```bash
PORT=5001
DATABASE_URL=your_neon_db_url
NODE_ENV=development
```

### Mobile Application Setup (`/mobile`)

Create a `.env` file in the mobile directory with:

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## 🚀 Getting Started

### Backend Server

To start the backend development server:

```bash
cd backend
npm install
npm run dev
```

The server will be running on the port specified in your `.env` file (default: 5001) 🖥️

### Mobile Application

To launch the mobile application:

```bash
cd mobile
npm install
npx expo start
```

Scan the QR code with Expo Go app or run on your preferred platform (iOS/Android/Web) 📱

---

## 🎯 Project Structure

```
react-native-recipe-app-master/
├── backend/          # Express API server (TypeScript)
├── mobile/           # React Native app (TypeScript/Expo)
└── README.md         # This file
```

---

## 💡 Tech Stack Details

- **Frontend**: React Native with Expo Router
- **Backend**: Express.js with TypeScript
- **Database**: PostgreSQL (via Neon)
- **Authentication**: Clerk
- **Styling**: React Native StyleSheet
- **State Management**: React Hooks

---

## 📝 Notes

- Make sure to configure your environment variables before running the application
- The backend server must be running for the favorites feature to work
- This project is fully written in TypeScript for better type safety and developer experience

---

<p align="center">Happy Cooking! 👨‍🍳👩‍🍳</p>