# Habibi Dessert POS Android V7

This source includes the Android WebView wrapper and V7 storage fix. It builds an installable debug APK using GitHub Actions.

To download: Actions > Build Habibi POS APK > latest successful run > Artifacts > HabibiPOS-V7-APK. Extract app-debug.apk and install it on the Galaxy Tab.

Test saving orders, open shifts, products, PayNow, and JSON backup before use. Do not uninstall the app without exporting data. The debug certificate from GitHub runners is not guaranteed to remain consistent across builds. Default credentials must be changed. The PayNow QR JavaScript library is loaded from a CDN, so the QR may require Internet.
