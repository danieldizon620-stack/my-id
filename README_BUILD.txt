MY-ID Android App v3.0
======================
A WebView Android application for https://my-id.alwaysdata.net/
Includes the MY-ID blue/teal logo as launcher icon.

BUILD APK USING GITHUB:
1. Create a GitHub repository, e.g. my-id-android.
2. Upload the CONTENTS of this folder to the repository ROOT:
   app/, .github/, build.gradle, settings.gradle, gradle.properties, README_BUILD.txt
   (Do NOT upload the containing folder itself.)
3. Go to Actions > Build MY-ID APK > Run workflow.
4. After a successful build, open the run's Artifacts and download MY_ID_v3_0_APK.
5. Extract artifact ZIP to obtain app-debug.apk, then install on Android.

BUILD USING ANDROID STUDIO:
Open this folder as a project; sync Gradle; Build > Build APK(s).
Java 17, Android SDK 35 and Gradle 8.9 are required.

SECURITY:
- The app only allows the HTTPS MY-ID site in the WebView.
- Links to other hosts open externally.
- SSL errors are blocked.
- Credentials and documents stay on the existing website/server.
- This is a DEBUG APK for testing, not a signed production release.
- Downloading protected documents from inside the app is not yet implemented.
- Camera/photo picker behavior depends on Android WebView and installed camera apps.
- Test on an actual Android phone before using real IDs.
