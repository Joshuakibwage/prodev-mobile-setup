# My First Mobile App with Expo

## Objective
The goal of this task was to create my very first mobile app using the **Expo Router template**.  
I set up the project, explored the file structure, modified the home screen, and finally tested the app on my device using **Expo Go**.  

---

## Steps I Followed

### 1. Navigated to the Project Directory
I moved into my parent repo folder:
```bash
cd prodev-mobile-setup

2. Initialized a New Expo Project

I created a new Expo app using the latest Expo Router template:

npx create-expo-app@latest --template

This generated a new project with Expo Router already set up.
3. Modified the Home Screen

I opened:

app/(tabs)/index.tsx

Inside the file, there was a default text:

Welcome!

I changed it to:

** First App Created**

This was my first edit to the app’s UI.
4. Ran the Application

I started the Expo development server:

npx expo start

    On Android, I scanned the QR code using the Expo Go app.

    (For iOS, the Camera app would work, but I used Android for my setup).

When I scanned the code, my modified app with ** First App Created** text appeared on my phone 🎉.
5. Reset the Application

I ran:

npm run reset-project

My Observations

    The reset command cleared out cached files and re-initialized the project state.

    It felt similar to starting with a fresh clone — my edits were preserved in the source files, but the environment was reconfigured.

    This is useful when dependencies or cached builds cause issues.

File Structure I Noticed

After scaffolding, some important files and folders stood out:

    app/(tabs)/index.tsx → The home screen I modified.

    app-example/constants/Colors.tsx → Color definitions for styling.

    app-example/ → Example components and setup that came with the template.

Reflection

This was my first hands-on experience scaffolding a mobile app with Expo.
Compared to web apps, it felt very smooth to preview changes instantly on my phone using Expo Go. The reset-project command also gave me insight into how Expo manages cache and dependencies under the hood.

I now feel more confident about navigating an Expo Router project and making basic UI modifications.
Repository Structure

prodev-mobile-setup/
└── prodev-mobile-app-0x00/
    ├── README.md
    ├── app-example/
    │   ├── app/(tabs)/index.tsx
    │   └── constants/Colors.tsx
    └── ...


---
 