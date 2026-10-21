MY ID v5.5 — Android APK Build Project

This ZIP contains Android source and a GitHub Actions workflow. It is NOT a compiled APK.
The app opens https://my-id.alwaysdata.net/ and uses the live website. Deploy the
MY ID v5.5 PHP website update to display the 10% mobile top offset.

To compile using GitHub:
1. Extract this ZIP and upload all its contents, including .github/, to your GitHub repository's main branch.
2. Open GitHub > Actions > Build MY-ID APK > Run workflow.
3. Wait for the successful build and download artifact MY_ID_v5_5_APK.
4. Extract app-debug.apk and install it on your Android device.

You can also open the project in Android Studio and select Build > Build APK(s).
This is a debug APK, not a Play Store release. Requires internet access.
A server-side 403 Forbidden error will also appear in the Android app.
Do not overwrite or delete your server's vault.sqlite, secret.key, or encrypted documents.
