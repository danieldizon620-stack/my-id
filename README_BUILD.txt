MY ID Android App - Android Studio source project

This is a WebView wrapper for https://my-id.alwaysdata.net/.
It does not include the PHP backend and does not work offline.

Build an APK on Windows:
1. Install Android Studio from https://developer.android.com/studio
2. Open the MY_ID_Android_App folder as a project.
3. Allow Android Studio to download Gradle and Android SDK components.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the APK under app/build/outputs/apk/debug/app-debug.apk.
6. Transfer the APK to your Android phone and install it.

Current limitations:
- This source project has not been compiled/tested here (Android SDK unavailable).
- The file picker supports Android's standard document/photo selection; direct camera capture may depend on the device/browser and requires further native integration.
- Authenticated downloads are not implemented in the wrapper; open the site in Chrome to download files.
- MY ID server must be online, HTTPS-enabled and functional.
- Do not store real identity documents until the server is security reviewed.
- For production release, configure signing and app distribution appropriately.
