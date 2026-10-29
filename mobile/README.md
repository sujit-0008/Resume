# Ringbook — Android & iOS app

Native wrapper (Capacitor 7) around the web app in `../dialer`. Edit the app in `dialer/index.html`, then run `npm run sync` here.

## Android APK — no computer setup needed
Push this repo to GitHub. The **Ringbook Android APK** workflow (Actions tab) builds `app-debug.apk`.
Open the finished run → *Artifacts* → download **Ringbook-apk** → unzip → send the `.apk` to your phone → tap it → allow "Install unknown apps".

## Android — on your own computer
Install Node 22 and Android Studio, then:
```
npm ci
npm run sync
npx cap open android      # Android Studio opens → ▶ Run, or Build → Build APK
```
For Google Play: Build → Generate Signed Bundle (.aab), upload in Play Console ($25 one-time).

## iOS
Needs a Mac with Xcode. For your own iPhone a free Apple ID works (app expires after 7 days);
App Store / TestFlight needs the Apple Developer Program ($99/year).
```
npm ci
npm run sync
npx cap open ios          # Xcode → pick your team under Signing → ▶ Run on your iPhone
```
