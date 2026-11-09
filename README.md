# Black Clover: Magic Wars — Android Studio project

This is a playable Android WebView game prototype with 10 sequential levels:
1. Noelle  2. Yuno  3. Luck  4. Magna  5. Yami
6. Mereoleona  7. Nacht  8. Zenon (boss)  9. Dante (boss)  10. Lucifero (final boss)

## Build an APK
1. Install Android Studio (latest stable) on a computer.
2. Open this `BlackCloverMagicWars` folder in Android Studio.
3. Allow Gradle sync to finish (Android Gradle Plugin 8.7.3, Kotlin 2.0.21, SDK 35).
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio creates the debug APK under `app/build/outputs/apk/debug/app-debug.apk`.

The project uses a local HTML5 canvas game inside an Android WebView and needs no network permission. The game art is original stylized placeholder illustration, not official character artwork. This is a prototype; replace or expand the artwork, animation, sound, and combat balancing before publishing.
