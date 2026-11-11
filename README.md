# Reality Mod Launcher: downloads

This repository has **only the downloads** for the Reality Mod Launcher: the installer and, later, its update packages.
It holds no source code and no game files.

The launcher starts **Reality Mod**, the realism mod for Battlefield 3, running on **bf3-rs**: a new engine written from scratch that loads the game files of your own Battlefield 3 copy.

## Status

**QA test builds only.** These builds are for our closed test group. Expect bugs; please report them to the team.

## What you need

- **Windows 10 or 11, 64-bit.**
- **Your own installed copy of Battlefield 3,** from the EA app or Origin. The launcher finds it on its own or asks for the folder.
- **A Vulkan-capable graphics card with 4 GB of video memory or more.** Tested on an RTX 3050 and a GTX 1070.
- **About 2 GB of free disk space** for the launcher and engine, plus room for caches.
- **For online play:** a Steam account to sign in with. Test accounts must be approved by the team first.

## Install

1. Open **Releases** on the right and download the newest `RealityModLauncher-Setup.exe`.
2. Run it and follow the steps.
3. Start the **Reality Mod Launcher** from the Start menu or the desktop shortcut.
4. On the first start, confirm your Battlefield 3 folder if the launcher asks for it.

Automatic updates through the launcher are coming. Until then, download the newest installer from **Releases** again. Every package is signed, and the launcher checks it before it installs.

## Is this legal?

Yes. The project was built to stay within the law from the start, and it was reviewed by our lawyer before this release.

- **No game files are distributed.** Nothing here contains Battlefield 3 content: no textures, models, sounds, maps or game code. The engine reads them from **your own** installed copy, so you need to own the game.
- **Your game stays untouched.** The engine only *reads* your Battlefield 3 files. It never changes, repacks or adds anything in your game folder, and mod changes are applied in memory while the game runs.
- **No cracking, no DRM bypass.** The game's executable is never unpacked, decrypted, debugged or copied. The engine is our own code, written from scratch using public information and the game's own data files.
- **No EA services.** The launcher does not connect to, imitate or replace any EA, Origin or Battlelog service, and it does not let anyone play without owning the game. Multiplayer uses its own servers and its own network protocol.
- **Reality Mod content** is used with the permission of the Reality Mod team.
- **Third-party software** in the package (for example the Chromium Embedded Framework for the in-game interface) is used under its own open-source licence; the notices are included in the installation.

**Online accounts:** you only contact our account service (Hera, run by the Reality Mod team) when you press **Sign in**. It stores the Steam ID you sign in with and your player name; it never asks for or stores an EA account or a password.

## Trademarks

"Battlefield" and "Battlefield 3" are trademarks of Electronic Arts Inc. This project is not affiliated with, endorsed by or sponsored by Electronic Arts Inc. or DICE. Names are used only to say which game the mod runs with.

## Licence

The downloads are provided for personal use by the test group, as they are, without warranty. The engine and launcher are made by the bf3-rs team. The Reality Mod parts belong to the Reality Mod team and may not be extracted or redistributed separately.
