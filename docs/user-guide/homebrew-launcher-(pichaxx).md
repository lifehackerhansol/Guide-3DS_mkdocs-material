---
title: Homebrew Launcher (PicHaxx)
---

# Homebrew Launcher (PicHaxx)
---

## Required Reading

This method of using Seedminer for further exploitation uses your `movable.sed` file to gain access to the Homebrew Launcher using the PicHaxx exploit for the purposes of injecting an exploitable DSiWare title into the DS Download Play application. This method requires you to already own (or download) the free "Pokemon Picross" game from the eShop.

!!! tip ""
	If your device already has access to the Homebrew Launcher (whether through PicHaxx or another exploit), you can skip to [Frogtool](installing-boot9strap-(frogtool).md).

!!! warning "Already have Picross?"
	If you already have Pokemon Picross, this process will overwrite your game's save file!

## What You Need

* The free eShop game "Pokemon Picross"
* Your `movable.sed` file from completing [Seedminer](seedminer.md)
* The latest release of [the Homebrew Launcher](https://github.com/fincs/new-hbmenu/releases/latest)
* The [otherapp payload](https://deadphoenix8091.github.io/3ds/#otherapp) *(for your region, device, and version)*
    + If your current version is 11.14.0-46, select 11.13.0-45 for your version

## Instructions

### Section I - Prep Work

1. Copy `boot.3dsx` to the root of your SD card
1. Copy the otherapp payload to the root of your SD card and rename it to `otherapp.bin`
    + If you do not see the `.bin` extension, do not add it to the end of the filename
1. Create a folder named `3ds` on the root of your SD card if it does not already exist

### Section II - PicHaxx

1. Open [the PicHaxx Injector website](https://3ds.nhnarwhal.com/3dstools/pichaxx.php) on your computer
1. Select your `movable.sed` file
1. Select "Build and Download"
1. Wait for the process to complete
1. Navigate to `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `title` -> `00040000` -> `0017c100` -> `data` on your SD card
    + The `<ID0>` will be the same one that you used in [Seedminer](seedminer.md)
    + The `<ID1>` is a 32 character long folder inside of the `<ID0>`
1. Copy the newly downloaded `00000001.sav` file to the `data` folder on your SD card
    + Overwrite the old save file when prompted
1. Reinsert your SD card into your device
1. Power on your device
1. Launch "Pokemon Picross"
1. If the exploit was successful, your device will have loaded the Homebrew Launcher
    + You may see an error stating there are no applications found
1. Power off your device

!!! tip ""
	### Continue to [Installing boot9strap (Frogtool)](installing-boot9strap-(frogtool).md)
