# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.


## 0. Setting Up and Testing Your Mobile Development Environment Objective

Objective
Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we will be using the Expo Framework for React Native, which simplifies mobile app development and testing.

To successfully complete this task, ensure you have the following:

Node.js LTS installed
VS Code (our recommended IDE)
macOS, Linux, or Windows
Expo Go installed on your physical device (Android or iOS)
These tools are essential for completing the upcoming projects efficiently.

Instructions
By now, you should already have Node.js LTS, VS Code, and a compatible operating system installed. This task focuses on setting up Expo Go on your physical device.

Why Expo Go?
Unlike web development, mobile development relies on device emulators to test applications. However, keeping up with the ever-evolving mobile ecosystem (e.g., iPhone 7 → iPhone 16 Pro Max, various Android devices) can be costly in terms of hardware requirements.

Expo Go provides a cost-effective solution by allowing you to test and run your React Native applications directly on your physical device, supporting both iOS and Android seamlessly.

Steps to Install Expo Go
Visit the official Expo Go homepage: https://expo.dev/go.
Select the latest SDK version.
Click on Install for your device:
Android: Install from the Google Play Store.
iOS: Install from the Apple App Store.
Open the Expo Go app on your device.
Create a new account or log in if you already have one.
Document your setup process and any challenges faced in the README.md file. This will help you track your progress and troubleshoot any issues that arise during development.

## 1. Create Your First Mobile App

Objective:
Set up your first mobile application using the Expo Router template. Document the scaffolding process and understand the file structure of a React Native application using Expo.

Instructions:
Navigate to Your Project Directory

Open your terminal and move to your parent project directory:

cd prodev-mobile-setup

Set Up Your Project

Initialize a new Expo project using the latest Expo Router template:

npx create-expo-app@latest .

Modify the Home Screen

Open app/(tabs)/index.tsx.
Locate the default text Welcome!.
Change it to ** First App Created**.
Run and Test Your Application

Start the Expo development server with:

npx expo start

For iOS Devices: Scan the QR code in the terminal using your phone’s Camera app.
For Android Devices: Scan the QR code using the Expo Go app.
Reset the Application

Run the reset command and observe its effects:

npm run reset-project

Document what happens when you reset the project in your README.md file.

Ensure your README.md includes

Steps you followed for scaffolding.
Observations from thereset-project command.

## 2. Implementing Mobile Components in React Native

Objectives
In React Native, you work with predefined components that translate directly into native components on iOS and Android. These components act as the building blocks of your application, much like HTML elements (such as <div> and <p>) in web development.

For example: - Instead of <div> in web development, you use <View> in React Native. - Instead of <p> for text content, you use <Text>.

By leveraging these predefined components, React Native ensures that your app maintains the native look and feel on both platforms while keeping development efficient.

Styling in React Native
Just like in web development, where you use CSS to style HTML elements, React Native provides a flexible styling system that allows you to customize your components. Styling in React Native is typically done using JavaScript objects, similar to inline styles in React web applications.