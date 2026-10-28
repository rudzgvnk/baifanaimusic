# Baifan Music

Android online music player starter project with a blue liquid-glass UI.

## Features
- Search the Free To Use independent music catalog
- Stream/play/pause and skip to next search result
- Album artwork and artist/title display
- Favorite toggles (currently in-memory for this app session)
- Jetpack Compose UI with translucent glass-like cards

## Music API (no key required)
This app uses the official Free To Use public API:
- Base URL: `https://api.freetouse.com/v3`
- Search endpoint: `/music/tracks/search?query=...&limit=25`

No API key or account is needed according to the official docs:
https://freetouse.com/api

## Build APK on GitHub
1. Create a GitHub repository and upload the contents of this project.
2. Open the **Actions** tab. The workflow `Build Android APK` runs on push to `main`/`master`, or can be started manually with **Run workflow**.
3. Download `BaifanMusic-debug-apk` from the workflow run's Artifacts.

## Notes
- This is a starter project and has not been built/verified in this environment.
- Track availability depends on the API. Free To Use licensing permits free use under specific conditions; commercial use requires a paid license. Review the current license before distributing the app:
  https://freetouse.com/license
- Favorites are not persisted across app restarts yet.
