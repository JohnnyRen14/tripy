# Tripy - AI Travel Planning App

A personal AI-powered travel planning mobile application that generates custom itineraries based on your destination and preferences.

## Features

- 🎯 **AI-Powered Planning**: Generate complete travel itineraries using OpenAI
- 📍 **Destination Input**: Simply enter where you want to go
- 📅 **Customizable Plans**: Specify dates, budget, interests, and travel style
- 💾 **Local Storage**: Save and manage your travel plans locally
- 📱 **Mobile-First**: Built with React Native for iOS and Android

## Tech Stack

- **Frontend**: React Native
- **AI Integration**: OpenAI API
- **Storage**: AsyncStorage (local)
- **State Management**: React Context API
- **Navigation**: React Navigation

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- React Native CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)
- OpenAI API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/JohnnyRen14/tripy.git
cd tripy
```

2. Install dependencies
```bash
cd app
npm install
```

3. Set up your OpenAI API key
```bash
# Add your API key to the environment configuration
```

4. Start the development server
```bash
npx react-native run-ios     # For iOS
npx react-native run-android # For Android
```

## Project Structure

```
Tripy/
├── app/                    # React Native mobile app
│   ├── src/
│   │   ├── screens/        # App screens (Home, Plan, Settings)
│   │   ├── components/     # Reusable UI components
│   │   ├── services/       # OpenAI API and storage services
│   │   ├── context/        # React Context for state management
│   │   └── utils/          # Helper functions
│   ├── assets/             # Images, fonts, etc.
│   └── package.json
├── README.md
└── .gitignore
```

## Usage

1. Open the app
2. Enter your destination
3. Configure your preferences (dates, budget, interests)
4. Let AI generate your perfect travel plan
5. Save and view your plans locally

## Contributing

This is a personal project, but feel free to fork and modify for your own use.

## License

MIT License - feel free to use this code for your personal projects. 