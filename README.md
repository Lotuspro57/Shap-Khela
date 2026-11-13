# Shap khela

Full-screen snake game with health, poison and bomb hazards, eight snake levels and synthesized sound.
Plain HTML, CSS and JavaScript. No build step.

## Install on Android (recommended: PWA)

1. Create a GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Repo **Settings > Pages > Build and deployment > Source: GitHub Actions**.
3. Push to `main`. The *Deploy to GitHub Pages* workflow publishes the game at
   `https://<your-user>.github.io/<repo>/`.
4. On the phone, open that link in Chrome, tap the menu (three dots) and choose
   **Install app** (or **Add to Home screen**). It then opens full screen and works offline.

## Optional: build an APK

Run **Actions > Build Android APK > Run workflow**. When it finishes, download the
`shapkhela-debug-apk` artifact, unzip it and copy `app-debug.apk` to the phone.
Allow "install unknown apps" when Android asks. This is a debug build for personal use.
Change `appId` in `capacitor.config.json` if you want your own package name.
