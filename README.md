# PopcornMovies Web App

A minimal Android WebView wrapper that opens `https://popcornmovies.st/`.

## Build locally with Android Studio
1. Open this folder in Android Studio.
2. Let Gradle sync and install any requested Android SDK components (compile SDK 35).
3. Select **Build > Build APK(s)**.
4. The debug APK is at `app/build/outputs/apk/debug/app-debug.apk`.

## Build an APK using GitHub Actions
1. Create a GitHub repository and upload the contents of this folder (the `app` folder and root Gradle files must be at the repository root).
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** and click **Run workflow** (or push to `main`/`master`).
4. When the workflow finishes, open the run and download the `popcornmovies-debug-apk` artifact.
5. Extract the ZIP artifact to get `app-debug.apk`.

The workflow builds a debug APK. It is not a Play Store-signed release build.
