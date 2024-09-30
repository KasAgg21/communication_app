# Communications-App

## 📖 Overview

The **Communications-App** is a cutting-edge, secure communications platform offering encrypted messaging, voice, and video calls. This app ensures privacy and security across desktop, Android, and iOS platforms. Currently, this repository includes the Android version of the app, supporting end-to-end encryption, real-time messaging, and more.

---

## 🚀 Features

- **Secure Messaging**: End-to-End Encryption (E2EE) using Signal Protocol.
- **Firebase Authentication**: Secure user authentication.
- **Push Notifications**: Real-time notifications for new messages.
- **Profile Customization**: Update profile picture and status.
- **Multi-Factor Authentication (MFA)** (Planned).
- **Message Expiration** (Planned).

To run the **Communications-App** on your own device, follow these step-by-step instructions:

---

### 🛠 Prerequisites

- **Android Studio** installed on your machine.
- **Java Development Kit (JDK)** version 8 or higher.
- A **Firebase Account** for project setup and integration.

---

### 📲 Installation Steps

1. **Clone this repository to your local machine**

   Open your terminal (or Git Bash) and run the following command:

   ```bash
   git clone https://github.com/yourusername/Communications-App.git
Navigate to the project directory:

bash
Copy code
cd Communications-App
Open the project in Android Studio

Launch Android Studio.
Select File -> Open and choose the directory where you cloned the repository.
Wait for the project to sync. Android Studio will automatically fetch and install the necessary dependencies.
Create a Firebase Project

Go to the Firebase Console.
Click on Add Project to create a new Firebase project.
Follow the instructions to set up your project.
Add Firebase Configuration to the App

After creating the Firebase project, navigate to the Project Settings in Firebase.
Under Your Apps, click Add App and choose Android.
Follow the instructions and download the google-services.json file.
Place the google-services.json file in the app/ directory of your Android project.
Enable Firebase Services

In the Firebase Console, go to the following sections and enable the required services:

Firebase Authentication: Enable email/password or any third-party provider of your choice.
Firebase Realtime Database: Set up database rules for secure access to the data.
Run the App

Connect your Android device via USB or set up an Android Virtual Device (AVD) through Android Studio.

In Android Studio, click the green Run button or use the following Gradle command:

bash
Copy code
./gradlew assembleDebug
The app should now launch on your connected device or emulator.
