HEAVEN SURVIVORS — PHONE-ONLY PWA PACKAGE

This package contains:
- index.html: your HTML/CSS/JavaScript game
- manifest.json: installable web-app metadata
- sw.js: basic offline caching for the game shell
- icons/: 192px and 512px launcher icons

NEXT STEPS USING AN ANDROID PHONE
1. Extract this ZIP on your phone.
2. Create a new repository on GitHub (a public repository is simplest for free GitHub Pages).
3. Upload the CONTENTS of this folder to the repository root (index.html must be at the root).
4. In repository Settings > Pages, enable deployment from the main branch and root folder.
5. Wait for GitHub Pages to publish the site. Open its HTTPS URL and test the game.
6. Once the PWA is live, use PWABuilder to package the URL for Google Play.

Important:
- This is a PWA website package, NOT an APK/AAB yet.
- PWABuilder's Google Play packaging requires a live HTTPS PWA and produces an Android App Bundle.
- You must configure Digital Asset Links (assetlinks.json) after packaging for the full-screen Trusted Web Activity experience.
- Keep any signing key and passwords private and backed up.
- Google Play developer registration and publishing must be handled by an adult account holder for users under 18.
