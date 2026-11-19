TEMPLE DASH - ANDROID PROJECT

1. Extract this ZIP.
2. Open the TempleDashAndroid folder in Android Studio (File > Open).
3. Use JDK 17 and allow Gradle sync to finish. If Android SDK 35 is not installed, install it from SDK Manager.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the APK location (usually app/build/outputs/apk/debug/app-debug.apk).

The game is packaged in app/src/main/assets/index.html and loads offline in a fullscreen WebView.
The requested glowing text "BHAG KAUSHAL BHAG" is drawn behind the runner.

Note: the supplied game uses Canvas-based pseudo-3D perspective, not a full 3D engine such as Unity or Three.js. This package preserves the existing game and adds the name banner; a true 3D conversion is a separate larger rebuild.
