# React Native CLI Setup Guide

This repository contains the boilerplate for **AwesomeProject**, initialized using the latest React Native Community CLI.

---

## 🚀 Getting Started

### Prerequisites
Before initializing the project, ensure you have the following installed on your system:
* **Node.js** (LTS version recommended)
* **JDK 17** (Microsoft OpenJDK or Oracle)
* **Android Studio** (for SDK management)

### Initialization Command
To create a new project from scratch, the following command was used:
`npx @react-native-community/cli@latest init AwesomeProject`

---

## ⚙️ Environment Configuration

To ensure the build tools function correctly, configure the following **System Environment Variables**:

### 1. Primary Variables
| Variable | Value |
| :--- | :--- |
| **JAVA_HOME** | `C:\Program Files\Microsoft\jdk-17.x.x.x-hotspot` |
| **ANDROID_HOME** | `%LOCALAPPDATA%\Android\Sdk` |

### 2. Path Updates
Add the following entries to your system **Path** variable to enable global terminal commands:
* `%JAVA_HOME%\bin`
* `%ANDROID_HOME%\platform-tools`
* `%ANDROID_HOME%\emulator`

---

## 🛠️ Development Scripts

Navigate to the project directory and use the following commands to start developing:

### Step 1: Start Metro Bundler
The Metro bundler ships with React Native to compile your JavaScript code in real-time.
```bash
npm start
# OR
npx react-native start
```

### Step 2: Start Application
Let Metro Bundler run in its own terminal. Open a new terminal inside your React Native project folder. Run the following:
```bash
npm run android
# OR
npx react-native run-android