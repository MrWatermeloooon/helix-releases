# HELIX Launcher

The launcher for games made with the HELIX Engine. It installs every game, keeps them
updated automatically and updates itself.

## Install (once)

1. Download **[HELIX-Launcher.zip](https://github.com/MrWatermeloooon/helix-releases/releases/download/launcher/HELIX-Launcher.zip)**.
2. Extract it to any folder (for example `Documents\HELIX Launcher`).
3. Run `HELIXLauncher.exe`. Windows may show "Windows protected your PC" because the
   launcher isn't code-signed: click **More info**, then **Run anyway**.
4. Pick a game on the left and press **INSTALL**, then **PLAY**.

That's it. Whenever a game or the launcher is updated, the launcher downloads the update the
next time you open it; you never need to download anything by hand again.

Games are installed to `%LOCALAPPDATA%\HELIX\games`. Requirements: Windows 10 or 11 (64-bit)
and a graphics card with Vulkan 1.3 drivers (any GPU from the last several years).

## What's in this repository

Built games only (no source code): `catalog.json` is the list the launcher reads, `images/`
holds banners and icons, and each game version is a GitHub release.
