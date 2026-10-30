# Shop Manager - Android app

Aap ki index.html (app/src/main/assets/index.html) ko WebView mein chalane wala Android project.
Data phone ke andar hi save hota hai (localStorage). CSV/backup Downloads mein save hote hain, slip Print / Save PDF se nikalti hai, WhatsApp aur helpline call direct khulti hain.

## Tareeqa 1: GitHub se APK (computer ya Android Studio ke baghair)
1. github.com par free account banayen, naya repository banayen (e.g. shop-manager).
2. Is zip ka saara content (hidden folder .github samet) repository mein upload karen.
3. Repository mein Actions > Build APK > Run workflow dabayen.
4. 3-5 minute baad run ke Artifacts mein ShopManager-APK download karen, zip kholen aur app-debug.apk phone mein install karen.

## Tareeqa 2: Android Studio
1. Android Studio mein File > Open > is folder ko chunen.
2. Build > Build APK(s). APK yahan milti hai: app/build/outputs/apk/debug/app-debug.apk

## Index mein tabdeeli
app/src/main/assets/index.html badal kar dobara build karen. App ka naam: app/src/main/res/values/strings.xml.
Minimum Android 10.
