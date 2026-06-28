# FridgeChef AI - Play-ready Android project

This package contains a native Android WebView wrapper with the FridgeChef AI web app bundled inside `app/src/main/assets/www`.

## Build in Android Studio
1. Open Android Studio.
2. File > Open > select this folder: `fridgechef_play_ready`.
3. Let Gradle sync.
4. Build > Generate Signed Bundle / APK.
5. Select Android App Bundle (.aab).
6. Create or select a keystore.
7. Build the release `.aab`.
8. Upload the `.aab` to Google Play Console.

## App ID
`com.fridgechef.ai`

## Important before release
- Replace the demo AI recognition with real backend/AI before marketing it as real scanning.
- Add a real privacy policy URL in Play Console.
- Add screenshots, icon, feature graphic, data safety answers.
- Test on a physical Android phone.
