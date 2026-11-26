# StreakRise

Discipline & Learning Tracker. Created by Birendra Dangi, Copyright Reserved 2026.

## How to get the Android APK (no Android Studio needed)

1. Create a **private** repository on GitHub (the login password is stored inside `www/index.html`).
2. Upload every file and folder from this project, keeping the same structure
   (the hidden `.github` folder must be included).
3. Open the **Actions** tab. The build "Build StreakRise APK" starts by itself (about 5-8 minutes).
   If it does not, click it and press **Run workflow**.
4. When it shows a green tick, open the run and download **StreakRise-APK** from "Artifacts".
5. Unzip it, copy `app-debug.apk` to your phone, and install it
   (allow "Install unknown apps" when asked).

## Project layout

- `www/index.html` - the whole app
- `assets/` - app icon images (icon-only, foreground, background)
- `capacitor.config.json` - app name `StreakRise`, id `com.birendradangi.streakrise`
- `.github/workflows/build-apk.yml` - builds the APK in the cloud

## PDF features (inside the app)

- **View PDF** opens the report in your phone's PDF viewer.
- **Download PDF** saves it to `Documents/StreakRise/`.
- **Share PDF** opens the share sheet (WhatsApp, Drive, email...).

## Login

User ID and password are the constants `APP_USER` and `APP_PASS` at the top of the script in `www/index.html`.
