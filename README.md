# Open City – Prototype

A small original open-city browser game prototype. It uses simple 2D top-down art to keep the first build lightweight and easy to test.

## Play locally
Open `index.html` in a modern browser. On desktop use WASD/arrow keys, Shift to run, E to interact, Space for action, M for map. On mobile, use the on-screen controls.

## Build an Android APK with GitHub Actions
1. Push this project to the `main` branch.
2. Open the repository's **Actions** tab and run **Build Android APK** (or push a commit).
3. Wait for the workflow to finish.
4. Open the completed workflow run, scroll to **Artifacts**, and download `open-city-debug-apk`.
5. Extract the ZIP and install `app-debug.apk` on your Android phone. You may need to allow installation from that source.

This is a debug prototype APK, not a Play Store release. For a public release, configure a signed release keystore and app ID.

## Notes
- This is an early prototype, not a full 3D GTA-scale game.
- Train movement, stores, food, outfit changes, basic car interaction, map and mobile controls are included in simplified form.
- Sound effects are not included in this first build; clean sound mixing is planned for a later iteration.
