# MeterMonitoring

Standalone Android app for daily Meralco (kWh) and Manila Water (m³) meter readings.

## Features
- Automatic daily differences sorted by date
- Recalculates later differences when a missed day's reading is added
- Local device save, edit and delete records
- CSV export and print/save as PDF

## Download the APK
Open the **Actions** tab, select the latest successful **Build MeterMonitoring APK** run, then download the `MeterMonitoring-debug-apk` artifact and extract the APK.

## Build
GitHub Actions builds the debug APK automatically on each push to `main` or `master`. You can also run it manually from Actions.

Records are saved locally on the device and are not cloud-synced.
