# losinho.github.io

Root of the GitHub Pages domain. The app itself lives in the
[learning_app](https://github.com/losinho/learning_app) repository and is served at
https://losinho.github.io/learning_app/.

- `.well-known/assetlinks.json` — Digital Asset Links for the Android app (`io.github.losinho.twa`).
  It proves the app and the site have the same owner, so the APK opens full-screen without Chrome's
  address bar. The fingerprint is the SHA-256 of the signing key from the PWABuilder package; if the
  app is ever published on Google Play, add the Play Console's app-signing key fingerprint to the same list.
- `.nojekyll` — makes GitHub Pages serve dot-folders such as `.well-known`.
- `index.html` — sends visitors of the bare domain to the app.
