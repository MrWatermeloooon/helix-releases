# HELIX Launcher

One launcher for the games made by brandinho and friends: games built on the HELIX Engine and
games made with Unity, Unreal and more. It installs every game, keeps them updated
automatically and updates itself.

## Install (once)

1. Download **[HELIX-Launcher.zip](https://github.com/MrWatermeloooon/helix-releases/releases/download/launcher/HELIX-Launcher.zip)**.
2. Extract it to any folder (for example `Documents\HELIX Launcher`).
3. Run `HELIXLauncher.exe`. Windows may show "Windows protected your PC" because the
   launcher isn't code-signed: click **More info**, then **Run anyway**.
4. Pick a game in the **Library** and press **Install**, then **Play**.

That's it. Whenever a game or the launcher is updated, the launcher downloads the update the
next time you open it; you never need to download anything by hand again.

## Games

| Game | Made by |
| --- | --- |
| **SCRAPFALL** | brandinho |
| **Icarus: Crispy Feathers** | Antique (Anthony Vitalei-D'Ermes) |
| **Flush You** | James Van Aelst, Santiago Santos, Joseph Lodico, Antique (Anthony Vitalei-D'Ermes), Mark Benson Galvez, Alexandrine Beaulac |
| **IVendetta** | Antique (Anthony Vitalei-D'Ermes) |
| **Sentiment** | Marcel Taveau, Santiago Santos, James Van Aelst, Joseph Lodico, Lorenzo Marquez, Antique (Anthony Vitalei-D'Ermes), Olivia Vitalei-D'Ermes, Rawlings Oduwa |
| **Infinite Trigger** | Antique (Anthony Vitalei-D'Ermes) |
| **Sonic: Scuffed Edition** | Antique (Anthony Vitalei-D'Ermes) |

## Requirements

Windows 10 or 11 (64-bit). The launcher and HELIX Engine games need a graphics card with
Vulkan 1.3 drivers (any GPU from the last several years); each other game has the usual
requirements of its engine. Games are installed to `%LOCALAPPDATA%\HELIX\games`.

## What's in this repository

Built games only (no source code): `catalog.json` is the list the launcher reads, `images/`
holds banners and icons, and each game version is a GitHub release. Every game belongs to the
people who made it. This README is written by `tools/publish.py` from the catalog.
