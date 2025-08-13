# HybridApp (Cordova)
Hybrid login/signup → dashboard app.

## Cloud build (no local Gradle needed)
1. Create a new GitHub repo.
2. Upload all files from this folder.
3. Go to **Actions** → run **Build Android APK (Cordova)**.
4. Download artifact **HybridApp-debug-apk** → `app-debug.apk`.

## Local build (optional)
```bash
npm i -g cordova@12
cordova platform add android@12.0.1
cordova build android --debug
# APK path: platforms/android/app/build/outputs/apk/debug/app-debug.apk
```

UI lives in `www/` (index.html, css, js). Modify freely.
