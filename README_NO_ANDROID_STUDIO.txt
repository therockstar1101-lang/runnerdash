TEMPLE DASH - BUILD APK WITHOUT ANDROID STUDIO

This project includes a GitHub Actions workflow that builds the APK in the cloud.
You do NOT need Android Studio on your computer.

STEPS
1. Sign in to https://github.com/ (create a free account if needed).
2. Create a new repository. Name it TempleDashAndroid. Public or Private is your choice.
3. Extract this ZIP on your computer.
4. Open the new GitHub repository and choose Add file > Upload files.
5. Upload the CONTENTS of the extracted TempleDashAndroid folder (including the hidden .github folder).
   Important: the repository root should contain settings.gradle, build.gradle, app/, and .github/.
6. Commit the uploaded files to the main branch.
7. Open the repository's Actions tab. Select "Build Temple Dash APK" if shown, then click Run workflow.
   A push to main/master also starts a build automatically.
8. Wait for the workflow to finish with a green check mark.
9. Open the completed workflow run. Under Artifacts, download "Temple-Dash-APK".
10. Extract the downloaded artifact ZIP. It contains app-debug.apk. Transfer it to your Android phone
    and tap it to install. Android may ask you to allow installation from that source.

NOTES
- This produces a debug APK for testing, not a Play Store release APK.
- GitHub may ask you to verify your account before enabling Actions.
- The runner's tunic contains the text BHAG / KAUSHAL / BHAG; it is drawn on the character, not in the background.
