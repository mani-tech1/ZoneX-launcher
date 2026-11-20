# 🎯 Tap Zones

A lightweight, fully **offline** Android launcher where you place invisible tap zones anywhere on your home screen and make each one open an app of your choice.

No internet. No ads. No tracking.

---

## ✨ Features

- **Tap zones** – place as many as you like, move and resize them freely
- **Double-tap or single-tap** to open a different app from each zone
- **Multiple screens** – every screen has its own zones, and empty screens disappear automatically
- **9 screen movements** – Normal, Cube, Zoom, Fade, Rotate, Flip, Stack, Depth, Accordion
- **Digital clock** – 12/24-hour, day and date, battery %, custom size, color and position
- **Swipe up** for a full app list with icons, names and search (hide apps or turn any app into a zone)
- **Swipe down** to open the notification panel
- **Draw to launch** – draw a shape (like a **C** for Camera) and the app you saved for it opens
- **Customizable settings** – hold your finger on the home screen for 5 seconds to open them
- Dark and light themes, accent colors, wallpaper or solid background

---

## 🖐️ Gestures

| Gesture | Action |
|---|---|
| Double-tap a zone | Open its app |
| Single-tap a zone | Open its optional second app |
| Swipe left / right | Change screen |
| Swipe up | App list |
| Swipe down | Notifications |
| Draw a saved shape | Open the matching app |
| Hold ~1 second | Edit mode (add, move, resize zones) |
| Hold 5 seconds | Settings |

---

## 📲 Install

1. Download the APK from the **Actions** tab (latest successful run, **Artifacts**), or build it yourself below.
2. Extract the zip and install `app-debug.apk`.
3. Press Home and choose **Tap Zones** as your default home app.

> Google Play Protect may warn about apps installed outside the Play Store. This is expected for self-built apps.

---

## 🛠️ Build

**With Android Studio:** open the project folder and choose Build > Build APK(s).

**With GitHub Actions (no PC needed):** the workflow in `.github/workflows/build.yml` builds the APK on every push. Download it from the run's **Artifacts**.

**Requirements:** JDK 17, Gradle 8.7, Android SDK 34 (min SDK 24 / Android 7.0).

---

## 🧱 Tech

Kotlin · Android SDK only (no third-party libraries) · custom Canvas views · data stored locally with SharedPreferences

---

Built for fun and tinkering. Contributions and ideas are welcome. ⭐
