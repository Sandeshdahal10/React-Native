# React Native Library Management System

This is a **Library Management System** mobile app built with [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/). The app allows users to log in and manage library resources from their mobile device.

## Features

- **User Login:** Secure authentication with email and password.
- **Inline Toasts:** Instant feedback for login status and errors.
- **Modern UI:** Clean, responsive design using Tailwind CSS classes (via [NativeWind](https://www.nativewind.dev/)).
- **API Integration:** Connects to a RESTful backend for authentication and data.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Sandeshdahal10/React-Native.git
   cd React-Native/my-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the Expo development server:**
   ```sh
   npx expo start
   ```

4. **Run on your device:**
   - Use the Expo Go app (Android/iOS) to scan the QR code.
   - Or run on an emulator/simulator.

## Project Structure

```
my-app/
├── app/
│   ├── login.js         # Login screen
│   └── ...              # Other screens/components
├── assets/              # Images and static assets
├── package.json
└── ...
```

## API

- The app connects to:  
  `https://library-management-system-boo3.onrender.com/api/login`

## Customization

- Update API endpoints in `app/login.js` as needed.
- Style components using Tailwind classes or standard React Native styles.

## License

This project is for educational purposes.

---

**Made with ❤️ using React Native and Expo**