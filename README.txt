GHS SHAMDHARA ANDROID APP - SOURCE PROJECT

This Android app is a WebView wrapper for the existing online PHP website:
https://ghsshamdhara.liveblog365.com/

FEATURES
- Opens the existing hosted website inside an Android app.
- Internet connection required.
- JavaScript and browser storage enabled for PHP website functionality.
- Keeps website login cookies between app sessions.
- Android back button navigates website history.
- File chooser supports website upload controls.
- Download links are handled by Android Download Manager.
- External websites open in the phone browser.

BUILD APK (Windows)
1. Install Android Studio from https://developer.android.com/studio
2. Extract this ZIP file.
3. In Android Studio choose File > Open and select the GHSShamdharaAndroid folder.
4. Wait for Gradle sync. Install Android SDK Platform 35 if Android Studio asks.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When the build completes, click Locate. The APK is normally at:
   app\build\outputs\apk\debug\app-debug.apk
7. Copy app-debug.apk to your Android phone and install it. If prompted, allow installation from that source.

NOTES
- The app does not contain PHP or MySQL; those remain on your hosting account.
- Website changes appear in the app automatically because it loads the live website.
- If the hosting provider blocks the site or the site is down, the app cannot load it.
- This is a source project, not a prebuilt APK. It must be compiled with Android Studio/Android SDK.
