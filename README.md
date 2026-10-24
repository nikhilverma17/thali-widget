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
