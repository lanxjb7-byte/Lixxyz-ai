# Lixxzy Ai Android

Android Java WebView app for `https://lixxzy-ai.netlify.app`.

- App name: **Lixxzy Ai**
- Application ID: `com.lixxzy.ai`
- Minimum Android: 6.0 (API 23)
- Build: GitHub Actions (JDK 17, Gradle 8.9)

## Build APK on GitHub

1. Create a new GitHub repository.
2. Upload the contents of this ZIP to the repository root (do not upload the ZIP itself).
3. Open **Actions** and select **Build Lixxzy Ai APK**.
4. Press **Run workflow** (or push to `main` / `master`).
5. Wait for the workflow to finish successfully.
6. Open the completed run and download **Lixxzy-Ai-APK** under Artifacts.
7. Extract the artifact ZIP; install `app-debug.apk` on your Android phone.

The app loads the live website, so its in-app appearance and features follow the website. Website updates appear in the app without rebuilding the APK, as long as the site remains online and compatible with Android WebView.

## Notes

- Internet access is required.
- The file picker is enabled for website upload inputs.
- External links open in the browser.
- This project produces a debug APK. A release APK suitable for public distribution should be signed with a private signing key.
