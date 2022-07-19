## SMEFT but Sexy Readme

You will need to read through this readme thoroughly before you get going. Setting up to install SMEFT but Sexy requires a little more effort than a standard Wabbajack modlist as there's a couple extra things to download.

### Index

- [SMEFT but Sexy Readme](#smeft-but-sexy-readme)
  - [Index](#index)
  - [Important Information](#important-information)
  - [Description](#description)
    - [What's included?](#whats-included)
  - [Installation](#installation)
    - [Required Accounts](#required-accounts)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Installing .NET 6.0](#installing-net-60)
      - [Steam Config](#steam-config)
        - [Game Location](#game-location)

### Important Information

Wabbajack modlists install their OWN independent instance of Mod Organizer 2. They don't work with Mod Organizer instances you installed yourself.

This list might require the latest Steam version of Skyrim SE(Special Edition)/AE(Anniversary Edition) installed, BUT it will downgrade it to version **1.5.97** due to the greater compatibility of that version with mods. You can however still use the AE included and bought via DLC Creation Club mods.

How to use the Creation Club is explained [here](https://github.com/EzioTheDeadPoet/SME-FT-/tree/SMEFT-2.0#creation-club--anniversary-edition-upgrade-content).

If you want to learn more about modding Skyrim, you can read up on it on the [/r/skyrimmods wiki](https://www.reddit.com/r/skyrimmods/wiki/begin2) or follow the [Guides by Lively](https://github.com/LivelyDismay/Learn-To-Mod/wiki) & [modding resources by The-Animonculory](https://github.com/The-Animonculory/Modding-Resources) on how to get started and with Skyrim modding.

### Description

This modlist is a utility for modders, to speed up their initial modding setup, or for people who want to play vanilla Skyrim with all the unofficial patches and fixes. It can also be utilized as a test bench for developing new mods on a stable base.

#### What's included?

The list contains mods that fall into 4 categories.

**Tools**
- [BethINI](http://nexusmods.com/skyrimspecialedition/mods/4875)
- [BodySlide and Outfit Studio](http://nexusmods.com/skyrimspecialedition/mods/201)
- [deorder's MO2 Plugins](https://github.com/deorder/mo2-plugins)
    - **Merge Plugins Hide:** Hide / unhide plugins that were merged using Merge Plugins or zMerge.
    - **Sync Mod Order:** Sync mod order from current profile to another while keeping the (enabled/disabled) state intact.
- [Dynamic Distant Objects LOD - DynDOLOD](https://www.nexusmods.com/skyrim/mods/59721)
    - You need to reinstall the resources with your preferences.
- [LOOT](https://github.com/loot/loot)
- [Nemesis](https://www.nexusmods.com/skyrimspecialedition/mods/60033)
    - This replaces FNIS and is compatible with any FNIS mod (even the ones with outdated descriptions demanding FNIS), with the only exception being animations involving creatures, those are incompatible. Those creature animations would not be found on the Nexus so most people wont see a difference.
- [NifSkope](https://github.com/niftools/nifskope)
- [Papyrus Compiler App (Mod Organizer 2 Integration) SE](http://nexusmods.com/skyrimspecialedition/mods/23852)
- [SSEEdit](https://nexusmods.com/skyrimspecialedition/mods/164)
- [SSELODGen](https://www.nexusmods.com/skyrimspecialedition/mods/6642)
- [Synthesis](https://github.com/Noggog/Synthesis)
- [Unofficial Mator Smash Updated](https://www.nexusmods.com/skyrimspecialedition/mods/39378)
- [Wrye Bash](https://www.nexusmods.com/skyrimspecialedition/mods/6837)
- [zEdit](https://github.com/z-edit/zedit)

**Mods**

*Insert link to load order library here*

### Installation

#### Required Accounts

1. Nexus Mods - a premium account is highly recommended for automating downloads from Nexus mods.

#### Pre-Installation

These steps are only needed if you are installing this modlist for the first time.

##### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017 and 2019".

|[Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe)|

##### Installing .NET 6.0

This is a needed dependency for mods used with this list. So please make sure to install it to avoid any issues. Download the desktop app x64 AND the console app x64 versions from Microsoft.

[Direct Link Desktop](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.5-windows-x64-installer) | [Direct Link Console](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.5-windows-x64-installer)

##### Steam Config

###### Game Location

Make sure your game is NOT installed in a common folder like your Desktop, Downloads or Program Files folder (like the default steam location). If you only have one drive and can't create a second steam library with steam use LostDragonist's steam-library-setup-tool to create a second one on your main drive. When you have a new steam library setup move your game there using the steam feature to do so.
