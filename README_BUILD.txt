MY ID Android v5.3 — APK BUILD SOURCE
=====================================
This Android WebView app opens https://my-id.alwaysdata.net/
and displays the live MY ID website. To see v5.3 (immediate logo and
4-second animated boot), deploy MY ID v5.3 on the server first.

THIS FILE IS NOT A COMPILED APK. Android SDK/Gradle are not available
in this environment.

BUILD WITH GITHUB ACTIONS:
1. Extract this ZIP to a folder.
2. Upload all contents (including hidden .github folder) to the root
   of your GitHub repository on the main branch.
3. GitHub > Actions > Build MY-ID APK > Run workflow.
4. Wait for a successful build, download artifact MY_ID_v5_3_APK.
5. Unzip artifact and install app-debug.apk on Android.

Or open the project in Android Studio and Build > Build APK(s).
This is a debug-signed APK, not a Play Store release.
Requires internet access. The app does not bundle the PHP website.
If the website returns 403 Forbidden, the app will also show 403:
restore website access and ensure index.php is in the correct document root.
Do not replace your private server database, encryption key, or encrypted IDs.
