MY ID Android v5.6 — APK Build Project

This is Android source code with GitHub Actions APK compilation, NOT a compiled APK.
The Android WebView opens https://my-id.alwaysdata.net/ and uses the live website.

IMPORTANT: Install MY ID website v5.6 first. The 4-second boot plays once per
WebView session and should not replay when changing tabs.

Build APK:
1. Extract ZIP and upload all contents including hidden .github directory
   to the ROOT of a GitHub repository on branch main.
2. Go to Actions > Build MY-ID APK > Run workflow.
3. After the workflow succeeds, download artifact MY_ID_v5_6_APK.
4. Extract app-debug.apk from the artifact and install it on your Android phone.

Alternative: Open project in Android Studio, then Build > Build APK(s).
Requires an Internet connection. The debug APK is not Play Store signed.
A 403 error on the website will also affect the Android app.
Back up server files; never overwrite your private database, secret key or IDs.
