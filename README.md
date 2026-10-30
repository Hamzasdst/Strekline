# Streakline for Android

A habit tracker app. The whole app lives in `app/src/main/assets/index.html`.
Your habits are saved on the phone and work offline.

## Get the APK with GitHub (free, about 10 minutes, easiest on a computer)

1. Unzip this folder.
2. Sign in at github.com and create a new repository (click **+** then **New repository**, name it `streakline`, then **Create repository**).
3. On the new repository page, click **uploading an existing file**. Drag in everything from inside the unzipped folder, including the `app` and `.github` folders, then click **Commit changes**.
   - If the `.github` folder did not upload (it is hidden on some computers): click **Add file > Create new file**, type `.github/workflows/build-apk.yml` as the name, paste in the contents of `build-apk.yml.txt`, and commit.
4. Open the **Actions** tab. Wait for the **Build APK** run to turn green (about 3 to 5 minutes).
5. Open that run, scroll to **Artifacts**, and download **Streakline-APK**. Unzip it to get `app-debug.apk`.
6. Send the APK to your phone, open it, and allow "Install unknown apps" when Android asks.

## Or build it in Android Studio

Open this folder in Android Studio, wait for the sync, then choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Notes

- Needs Android 8.0 or newer.
- This is a debug-signed APK, fine for your own phone. It is not for the Play Store.
- Fonts download from Google the first time you are online. Without them the app uses your phone's default font.
- Habit data lives inside the app. Uninstalling the app erases it.
