# 💳 Fintech App  

## ✨ Overview  
A starter template for building a modern Fintech application using Expo and React Native.  
It provides the foundation for mobile banking or finance-related apps, including authentication, navigation, and ready-to-use UI components.  

---

## 🌍 Features  
- 🔑 **Authentication Flow** – registration, login, and biometric authentication  
- 📱 **Tabbed Navigation** – bottom tab navigator for main app sections  
- 🪟 **Modal Screens** – examples for sending money, adding cards, and viewing transaction details  
- 🧩 **UI Components** – reusable buttons, cards, and input fields  
- 🌐 **Context API** – global state management (authentication, theme, financial data)  
- 📝 **TypeScript Support** – strongly typed project for better maintainability  

---

## 🛠️ Tech Stack  

- **Framework:** React Native with Expo  
- **Routing:** Expo Router  
- **UI Enhancements:**  
  - React Navigation (navigation system)  
  - Expo Blur (blurred UI effects)  
  - Expo Linear Gradient (gradient backgrounds)  
  - Lucide React Native (icon set)  
- **Fonts:** Google Fonts (Inter)  
- **Language:** TypeScript  

---

## ⚙️ Getting Started  

### Prerequisites  
- Node.js (LTS recommended)  
- Expo Go app installed on a device, or an Android/iOS simulator  

### Installation  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   ```  
2. Move into the project folder:  
   ```bash
   cd fintech-app-master
   ```  
3. Install dependencies:  
   ```bash
   npm install
   ```  

### Running the App  
1. Start the development server:  
   ```bash
   npm run dev
   ```  
2. Scan the QR code in Expo Go, or press `a` for Android emulator / `i` for iOS simulator.  

---

## 📜 Available Scripts  
- `npm run dev` – start the Expo dev server  
- `npm run build:web` – build the project for web production  
- `npm run lint` – lint project files with Expo lint  

---

## 📂 Project Structure  

```
.
├── app/                      # Main application source code
│   ├── (tabs)/               # Tab-based navigation layout and screens
│   ├── auth/                 # Authentication-related screens
│   ├── modals/               # Modal screens
│   ├── _layout.tsx           # Root layout for the app
│   └── +not-found.tsx        # Not found screen
├── assets/                   # Static assets like images and fonts
├── components/               # Reusable UI components
│   ├── auth/                 # Authentication-specific components
│   ├── modals/               # Modal-specific components
│   └── ui/                   # Generic UI components
├── contexts/                 # React Context providers for global state
├── hooks/                    # Custom React hooks
├── styles/                   # Global styles (if any)
├── utils/                    # Utility functions
├── .gitignore
├── app.json                  # Expo configuration file
├── package.json              # Project dependencies and scripts
└── tsconfig.json             # TypeScript configuration
```

---

## 🙌 Notes  
This template is designed to speed up development of finance-related apps and can be easily customized with additional features or branding.  
