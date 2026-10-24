# Thali Widget (Android)

Home-screen widget for the Thali calorie tracker. It shows today's calories, what's left, and water, and refreshes every 15 minutes. Tap ↻ to refresh now, or tap the widget to open the tracker.

## Build the APK without installing anything (GitHub)
1. Create a free GitHub account and a new repository.
2. Upload all the files in this folder (keep the folder structure, including `.github`).
3. Open the **Actions** tab. The "Build APK" job starts automatically (or click **Run workflow**).
4. When it finishes with a green tick, open the run and download **thali-widget-apk** under Artifacts.
5. Unzip it on your phone and open `app-debug.apk`. Allow "Install unknown apps" for your browser or Files app when asked.

## Or build with Android Studio
Open this folder in Android Studio, wait for Gradle sync, then use Build → Build APK(s).

## Set up
1. Open **Thali Widget**, paste your data link from Thali (Me tab → Show my widget link), and tap **Save and test**.
2. Long-press your home screen → Widgets → **Thali Widget** → drag it onto the screen.

## Step counting (no other app needed)
NutriLog counts steps with the phone's own step sensor. The first time you open the app, tap **Allow** on the "Physical activity" prompt.
The sensor keeps counting by itself, and NutriLog reads it every 15 minutes, when you open the app, when you tap ↻ on a widget, and just after midnight.
Steps are counted from the moment you allow it (or from the last restart if that was today). Add the **NutriLog steps** widget from Widgets. Make it taller to see the last 7 days.
Steps always come from the phone's own sensor. Health Connect (where Google Fit saves its data) is optional and only used for distance, active calories, sleep and workouts.
If a phone has no step sensor, the widget says so. Allow "Unrestricted" battery use for NutriLog if your phone stops it from running in the background.
