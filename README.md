# HELIX Launcher

One launcher for the games made by brandinho and friends: games built on the HELIX Engine and
games made with Unity, Unreal and more. It installs every game, keeps them updated
automatically and updates itself.

## Install (once)

1. Download **[HELIX-Launcher-Setup.exe](https://github.com/MrWatermeloooon/helix-releases/releases/download/launcher/HELIX-Launcher-Setup.exe)** and run it. Windows may show "Windows
   protected your PC" because the launcher isn't code-signed: click **More info**, then
   **Run anyway**.
2. Click through the setup. It installs the launcher for your Windows account (no admin
   needed), adds Start menu and desktop shortcuts, and opens it.
3. Pick a game in the **Library** and press **Install**, then **Play**.

To remove it later, uninstall **HELIX Launcher** from Windows' Installed apps. Prefer no
installer? [HELIX-Launcher.zip](https://github.com/MrWatermeloooon/helix-releases/releases/download/launcher/HELIX-Launcher.zip) is the same launcher: extract it anywhere and run
`HELIXLauncher.exe`.

That's it. Whenever a game or the launcher is updated, the launcher downloads the update the
next time you open it; you never need to download anything by hand again.

## Games

| Game | Made by | Linux |
| --- | --- | --- |
| **SCRAPFALL** | brandinho | - |
| **Icarus: Crispy Feathers** | Antique (Anthony Vitalei-D'Ermes) | - |
| **Flush You** | James Van Aelst, Santiago Santos, Joseph Lodico, Antique (Anthony Vitalei-D'Ermes), Mark Benson Galvez, Alexandrine Beaulac | - |
| **IVendetta** | Antique (Anthony Vitalei-D'Ermes) | - |
| **Sentiment** | Marcel Taveau, Santiago Santos, James Van Aelst, Joseph Lodico, Lorenzo Marquez, Antique (Anthony Vitalei-D'Ermes), Olivia Vitalei-D'Ermes, Rawlings Oduwa | - |
| **Infinite Trigger** | Antique (Anthony Vitalei-D'Ermes) | - |
| **Sonic: Scuffed Edition** | Antique (Anthony Vitalei-D'Ermes) | - |
| **Tempest Island** | Antique (Anthony Vitalei-D'Ermes) | - |

### Linux

Download **[HELIX-Launcher-linux.zip](https://github.com/MrWatermeloooon/helix-releases/releases/download/launcher/HELIX-Launcher-linux.zip)**, unzip it anywhere and run `./HELIXLauncher`
(64-bit, X11 or Wayland). It installs and updates the games that have a Linux version (the Linux
column below); games are installed to `~/.local/share/HELIX/games`.

## Requirements

Windows 10 or 11 (64-bit), or 64-bit Linux. The launcher and HELIX Engine games run on Vulkan,
DirectX 11, DirectX 12 or OpenGL 3.3, whichever the PC has (any GPU from the last ten years); each
other game has the usual requirements of its engine. On Windows, games are installed to
`%LOCALAPPDATA%\HELIX\games`.

## What's in this repository

Built games only (no source code): `catalog.json` is the list the launcher reads, `images/`
holds banners and icons, and each game version is a GitHub release. Every game belongs to the
people who made it. This README is written by `tools/publish.py` from the catalog.
