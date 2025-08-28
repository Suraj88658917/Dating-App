
Amore - Dating & Relationship App

Welcome to "Amore", a sleek and modern dating app designed to help people connect and build relationships easily using "React Native" and "Expo".

 

     🚀 Overview

Amore is a cross-platform mobile app that offers an elegant, performant, and feature-rich experience for finding connections. Built with cutting-edge libraries and technologies, it ensures smooth animations, robust state management, and a seamless user experience.

 

     ✨ Key Features

- 📱 "Multi-platform" support (iOS & Android) with Expo SDK 48
- 🎨 "Styled Components" for modular and customizable styling
- 🛠 "Powerful Navigation": React Navigation stack, top tabs & animations
- 🌐 "GraphQL Integration" ready for dynamic data fetching
- 💾 "Persistent Redux Store" with Redux Persist & Redux Toolkit
- 🎭 "Interactive UI" with Lottie animations and React Native Reanimated
- 📡 Offline/Online detection with React Native NetInfo
- ⏳ Loading placeholders for smooth content display with react-content-loader
- 🔄 Hot reloading supported for rapid development during coding

 

     🔍 Technology Stack

| Layer             | Technology                          |
|-------------------|-----------------------------------|
| Framework         | React Native (0.71.3), Expo (48)  |
| State Management  | Redux Toolkit, Redux Saga, Reselect |
| Networking       | Axios, GraphQL                    |
| Navigation       | React Navigation v6               |
| Styling          | styled-components                 |
| Animations       | Lottie, React Native Reanimated  |
| Utilities        | lodash, moment                   |
| Build Tools      | Babel, Metro Bundler              |
| TypeScript       | Strongly typed codebase           |

 

     📁 Project Structure


.
├── src
│   ├── assets                 Images, animations, fonts, icons
│   ├── components             Reusable UI components & elements
│   ├── constants              Application-wide constants & enums
│   ├── graphql                Queries, mutations & schemas
│   ├── store                  Redux store, reducers, sagas
│   ├── services               API & backend service calls
│   ├── themes                 Styling, theming & colors
│   └── views                  Application screens & pages
├── App.json                  Expo app configuration
├── babel.config.js           Babel plugins & presets configuration
├── metro.config.js           Metro bundler configuration (SVG support)
├── package.json              Node dependencies and scripts
└── tsconfig.json             TypeScript compiler options


 

     🛠 Installation & Setup Guide

Follow these steps to set up Pegava locally on your machine:

       Prerequisites

- Node.js (recommended version 16+)
- Yarn or npm package manager
- Expo CLI (npm install -g expo-cli)

       Steps

1. "Clone the repository:"

bash
git clone https://github.com/YOUR_USERNAME/pegava-dating-app.git
cd pegava-dating-app


2. "Install dependencies:"

Using npm:

bash
npm install


Using Yarn:

bash
yarn


3. "Start the Expo development server:"

bash
npm start


4. "Run on an emulator or device:"

- For Android:

bash
npm run android


- For iOS:

bash
npm run ios


Or scan the QR code with the Expo Go app on your physical device.

 

     🔧 Configuration Details

- The app scheme is pegava for deep linking and navigation.
- Android package identifier is br.com.pegava.
- Splash screen and app icons located at src/assets/images/.
- Metro bundler configured to support .svg files via react-native-svg-transformer.
- Babel configured with plugins including styled-components and reanimated support.
- TypeScript path aliases configured for cleaner imports (e.g., ~components, ~services).

 

     🤝 How to Contribute

Contributions make the community better! Follow these simple steps to contribute:

- Fork the repository 🍴
- Create a feature branch: git checkout -b feature/your-feature
- Commit your changes: git commit -m "Add your feature"
- Push to your branch: git push origin feature/your-feature
- Open a Pull Request with detailed explanations 🎉

 

     🧪 Testing & Debugging

- Use Reactotron for Redux and Saga debugging.
- Redux DevTools compatible.
- Enable hot reloading and fast refresh through Expo for faster iteration.

 

     📝 Code Style

- Written in TypeScript for static type checking.
- Styled-components for CSS-in-JS styling.
- Follow the alias paths from tsconfig.json for imports.
- Modular, reusable components structure.

 

     📈 Roadmap & Ideas

- User profile customization
- Matchmaking algorithms
- Real-time chat integration
- Push notifications & alerts
- Social media login options

 

     

 

     💡 Need Help?

If you encounter any problems or want to request features, please open an issue here on GitHub.

 

     ⭐ Show Support

If you like this project, give it a ⭐ star to help it grow!

 


 

If you want badges (Expo version, React Native, License) or any other details added, just ask!

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/2ef69e30-6b68-43ea-b3f2-709d6b01417a/App.json)
[2](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/d18c6e15-457b-4b81-9a3b-1c83463a5e3d/babel.config.js)
[3](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/87cec705-9726-4621-b23e-d82b9baac559/metro.config.js)
[4](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/484d2287-8c36-4dd4-832d-11f03a4cad59/package.json)
[5](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/a939b3f0-1808-4655-bdc1-2d85579d8aae/package-lock.json)
[6](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85965836/deb511cd-b9c4-495a-a0ad-44f9df8eebc7/tsconfig.json)
