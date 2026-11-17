ONLINE APK BUILD - NO ANDROID STUDIO REQUIRED

1. Sign in or create a free account at https://github.com/
2. Click the + button (top right) > New repository.
3. Repository name: GHS-Shamdhara-Android
4. Choose Public (recommended for easiest free Actions access), tick Add a README file, then Create repository.
5. On the repository page click Add file > Upload files.
6. Extract this ZIP on your laptop. Open the extracted GHSShamdharaAndroid folder.
7. Select and upload ALL files and folders INSIDE that folder, including the .github folder. Do not upload only the ZIP file and do not upload the outer folder as a nested folder.
8. At the bottom click Commit changes.
9. Click the Actions tab. Open "Build GHS Shamdhara APK". If prompted, enable GitHub Actions.
10. If the workflow did not start automatically, click Run workflow > Run workflow.
11. Wait for the run to finish with a green check mark. Open that run and find Artifacts.
12. Download "GHS-Shamdhara-APK". Extract the downloaded ZIP; inside is app-debug.apk.
13. Send app-debug.apk to your Android phone and tap it to install. If Android asks, allow installing unknown apps for the app you used to open the APK.

IMPORTANT:
- Do not upload your PHP website database password or hosting credentials. This Android project only opens your existing public website.
- The APK needs internet to access https://ghsshamdhara.liveblog365.com/.
- The APK built by this workflow is a debug/test APK, suitable for installing on your phone. It is not a Play Store release-signed APK.
