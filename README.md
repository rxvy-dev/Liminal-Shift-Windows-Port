# BELOW ROUTE 9 — Windows

A first-person Backrooms horror game, shot on a 1998 camcorder. **Current version: 2.14.0**

## Download and play

- **[Below-Route-9-Setup.exe](https://github.com/rxvy-dev/below-route-9-windows/raw/refs/heads/main/Below-Route-9-Setup.exe)**: the installer. Run it and follow the wizard. It installs for your user only (no admin prompt) and adds Start Menu and desktop shortcuts.
- **[Below-Route-9-windows-portable.zip](https://github.com/rxvy-dev/below-route-9-windows/raw/refs/heads/main/Below-Route-9-windows-portable.zip)**: no install. Unzip it anywhere and run `below-route-9.exe` (keep the `textures` folder next to it).

Windows SmartScreen may say "Windows protected your PC" because the game isn't code-signed. Click **More info**, then **Run anyway**.

**Updating:** download the new installer and run it; it installs over the old version. For the portable version, unzip the new one into a fresh folder. Your saves and settings are kept either way.

If the picture looks clean, with no camcorder look, open **Options** and check that **CAMCORDER FILTER** is ON.

You need a GPU with OpenGL 3.3 (anything from roughly 2010 on).

## Source

`Below-Route-9-windows(1).zip` is the full source code, with the script that builds the installer from Linux (`packaging/windows/build-windows.sh`).

The Linux version is at [rxvy-dev/below-route-9](https://github.com/rxvy-dev/below-route-9).
