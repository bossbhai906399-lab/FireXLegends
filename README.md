# FireX Legends

A simple Android 2D shooting game built with Kotlin and Android Canvas.

## Build the APK from GitHub on an Android phone

1. Upload **all files and folders** from this project to the root of your GitHub repository.
2. Make sure this file exists exactly at `.github/workflows/build-apk.yml`.
3. Open the repository and tap **Actions**.
4. Open **Build FireX Legends APK**.
5. If it has not already started, use **Run workflow** and select `main`.
6. Wait for the run to show a green checkmark.
7. Open the successful run.
8. Scroll to **Artifacts** and download **FireX-Legends-APK**.
9. Extract the downloaded ZIP and install `app-debug.apk` on your Android phone.

The workflow also runs automatically whenever you push a change to the `main` branch.

## Game controls

- Drag/touch to aim.
- Tap **FIRE** to shoot.
- Enemies approach from four directions.
- Destroying an enemy gives +10 score.
- HP decreases when an enemy reaches the player.
- Game over appears when HP reaches 0.
- Tap **PLAY AGAIN** to restart.

No API key, server, database, or external game asset is required.
