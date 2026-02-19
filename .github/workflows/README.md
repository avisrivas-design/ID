# ID Card Maker

A professional Android WebView wrapper for the [PrintTech ID Cards](https://printtechidcards.netlify.app/) web application. This project converts the web-based ID card generation platform into a native-like mobile experience.

---

## 🚀 How to Get the APK (Easiest Method)

This repository is pre-configured with **GitHub Actions**, meaning you don't need Android Studio installed on your computer to generate the APK.

1.  **Create a new repository** on your GitHub account.
2.  **Upload all files** from this project folder to your new repository.
3.  Navigate to the **"Actions"** tab at the top of your GitHub repository.
4.  You will see a workflow named **"Build Android APK"** running automatically. Wait approximately 2–3 minutes.
5.  Once the process finishes, click on the completed run.
6.  Scroll down to the **"Artifacts"** section to download your generated `app-debug.apk` or `app-release.apk`.

---

## 🛠️ Alternative Method (Manual Build)

If you prefer to build the project locally for development or customization:

1.  Download and install [Android Studio](https://developer.android.com/studio).
2.  Clone this repository or open the project folder.
3.  Wait for Gradle sync to complete.
4.  Connect your Android device or start an emulator.
5.  Click **Run > Run 'app'** or use the **Build > Build APK** menu.

---

## 🔒 Required Permissions

To ensure full functionality of the web application (including photo uploads, location tagging, and voice input), the following permissions are integrated:

| Permission | Purpose |
| :--- | :--- |
| `INTERNET` | To load the WebView content. |
| `CAMERA` | For capturing profile photos directly. |
| `ACCESS_FINE_LOCATION` | For location-based features on the ID card. |
| `READ_EXTERNAL_STORAGE` | To select existing photos from the gallery. |
| `WRITE_EXTERNAL_STORAGE` | To save generated ID cards to the device. |
| `RECORD_AUDIO` | To support voice-enabled inputs/features. |

---

## 📱 Features

-   **Full Screen Experience:** Removes browser toolbars for a native app feel.
-   **JavaScript Enabled:** Full support for the interactive elements of the PrintTech site.
-   **File Upload Support:** Seamless integration with the Android file picker and camera.
-   **Responsive Design:** Optimized for various screen sizes and orientations.

## 🌐 Web Source
The app serves as a wrapper for: [https://printtechidcards.netlify.app/](https://printtechidcards.netlify.app/)

---

*Developed for streamlined ID card creation.*