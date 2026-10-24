# Number Magic Android

A minimal Android app for a number magic routine. Keep the app open and the screen on. Each physical Volume Up press advances the hidden count from 1 to 9, then wraps back to 1. Volume Down reveals the current count. The app intercepts volume keys while its activity is in the foreground; Android/system behavior can vary by device.

## Build

Push to GitHub and open **Actions**. The `Build Number Magic APK` workflow runs on push to `main` or can be started manually. Download `NumberMagic-debug` from the workflow run's Artifacts section.
