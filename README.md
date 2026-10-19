# THE THING - Android app

Your app is the file app/src/main/assets/index.html (same as THE_THING.html).
To change the app later, replace that file and build again.

## Build the APK with GitHub (no installs, free)
1. Go to github.com and sign up (free). Confirm your email.
2. Click the + at the top right, then "New repository". Name it `the-thing`, keep it Private, tick
   "Add a README file", then click "Create repository".
3. Unzip THE_THING_android.zip on your computer. Open the unzipped folder.
4. In your repository click "Add file" > "Upload files". Select everything INSIDE the folder
   (app, gradle, build.gradle, gradle.properties, settings.gradle) and drag it into the page.
   Click "Commit changes".
5. Click "Add file" > "Create new file". In the name box type exactly:
   .github/workflows/build-apk.yml
   Paste the contents of build-apk.yml (provided next to this zip), then "Commit changes".
6. Click the "Actions" tab. A run called "Build APK" starts by itself (yellow dot). Wait 3 to 6 minutes
   for a green tick. If you see nothing, click "Build APK" on the left, then "Run workflow".
7. Click the finished run, scroll to "Artifacts", and download THE-THING-apk. Unzip it to get app-debug.apk.
8. Copy app-debug.apk to your phone, tap it, and allow "Install unknown apps" if Android asks.

Your data (habits, attendance, timetable) is stored on the phone. Uninstalling the app erases it.
