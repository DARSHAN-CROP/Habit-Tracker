# Habit Tracker (ટેવ ટ્રેકર)

Daily habit tracker with streaks and a 7-day view (Gujarati and English).

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) ![Languages: Gujarati + English](https://img.shields.io/badge/languages-Gujarati%20%2B%20English-blue)

**Live demo (phone and PC, no install):** https://1darshankumarsavsani-blip.github.io/Habit-Tracker/

## Features

- Add daily habits and tick the last 7 days
- Current streak and best streak
- Progress bar for today
- Gujarati and English

## Download

Latest release (V1.0): `Habit_Tracker.apk` (Android, works offline) and `Habit_Tracker_Windows.exe` (opens the website in its own window; needs Edge or Chrome). See the [Releases page](../../releases/latest).

## Tech stack

- Web: single-file HTML/CSS/JavaScript, no libraries
- Android: a small Java WebView wrapper that bundles the same page offline

## Project structure

```text
docs/   website (single index.html, GitHub Pages)
app/    Android wrapper (Java) with the page in app/src/main/assets
release/  release files
.github/  issue templates and release workflow
```

## Build from source

Open the `app/` project in Android Studio, or run:

```bash
./gradlew assembleRelease     # build the APK (sign it with your own keystore)
```

Requirements: JDK 17, Android SDK 34. The website needs no build: open `docs/index.html` in a browser.

## Privacy

Everything stays in your browser or phone storage. Nothing is sent anywhere.

## Honest notes

Tested in a headless browser only. The APK and exe have not been run on a real phone or PC yet.

## Contributing

Bug reports and ideas are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and the issue templates. Please report security problems as described in [SECURITY.md](SECURITY.md).

## License

MIT, see [LICENSE](LICENSE).

## Author

Darshankumar Savsani, DARSHAN CORPORATION, Rajkot. GitHub: [1darshankumarsavsani-blip](https://github.com/1darshankumarsavsani-blip), organization: [DARSHAN-CROP](https://github.com/DARSHAN-CROP).
