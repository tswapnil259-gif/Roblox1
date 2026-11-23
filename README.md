# Roblox AI Studio Assistant (APK-Ready)

## Option 1: Free Cloud Build via GitHub (No PC / No Android Studio Needed)
1. Create a new repository on GitHub (e.g., `roblox-ai-studio`).
2. Unzip this file and upload all files (including the hidden `.github` folder!) to your GitHub repository.
3. Open the **Actions** tab in your GitHub repository.
4. Click on the **Build Android APK** workflow run (or click **Run workflow**).
5. Once finished (~2 minutes), scroll down to **Artifacts** and download **RobloxAiStudioAssistant-debug-apk** — unzip it to get your `.apk` file!

## Option 2: Android Studio (PC)
1. Unzip this folder and open it in **Android Studio**.
2. Wait for **Gradle Sync** to finish.
3. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Find your APK in `app/build/outputs/apk/debug/app-debug.apk`.
