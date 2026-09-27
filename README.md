# MedDroid — Android app (download)

This **public** repo exists only to host the downloadable **MedDroid Android APK** so it
can be served fast and unauthenticated, letting the main app repo stay **private**.

## Download
**[⬇️ meddroid.apk](https://raw.githubusercontent.com/sanjaydoc/meddroid-android-app/main/meddroid.apk)**

Direct link (used by the website + in‑app download buttons):
```
https://raw.githubusercontent.com/sanjaydoc/meddroid-android-app/main/meddroid.apk
```

## How it's published
The APK is built and pushed here automatically by the **`android-apk`** GitHub Actions
workflow in the private source repo `sanjaydoc/medicalandroid`, using a fine‑grained PAT
(`ANDROID_APP_REPO_TOKEN`, Contents: Read/Write on this repo). No source code lives here —
just the built APK and this README.

> MedDroid provides general medical information, not diagnosis. Always consult a clinician.
