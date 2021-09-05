# 3DS Hacks Guide
___
A complete guide to 3DS custom firmware, from stock to boot9strap.

!!! danger "Warning" Thoroughly read all of the introductory pages (including this one!) before proceeding.

!!! danger "Latest System Software" The latest system software version is currently 11.15.0-47. If you have installed CFW in the past, it is highly recommended to follow [Checking for CFW](extras/checking-for-cfw.md) to make sure your custom firmware is up-to-date.

## What is custom firmware?

**Custom firmware** ("CFW") is a full software modification to your 3DS, comparable to "administrator access" on a computer. It allows you to do anything that the 3DS is physically capable of doing, rather than being limited by whatever Nintendo allows you to do.

Popular uses for custom firmware include:

* Bypassing the region lock, allowing you to play games from other regions
* Home menu customization, using community-created [themes and badges](https://themeplaza.art)
* Modification of games ("ROM hacks") through [LayeredFS](https://github.com/knight-ryu12/godmode9-layeredfs-usage/wiki/Using-Luma3DS'-layeredfs-(Only-version-8.0-and-higher))
* Save data editing, backup, and restore
* Emulation of older consoles, as well as native playback of DS and GBA games
* Installing your physical cartridges for digital use

## What does this guide install?

This guide will install **boot9strap + Luma3DS custom firmware** on **unmodified/stock** 3DS/2DS devices. If you have installed custom firmware in the past, you should follow [these instructions](extras/checking-for-cfw.md) to find the correct upgrade path for your console. A modern, boot9strap/Luma3DS-based setup is preferred over older setups (arm9loaderhax, menuhax) because it is more stable for modern homebrew and continues to be supported by the community.

## What do I need to know before starting?

* While the risks of bricking have been minimized over the years, **we are not responsible for anything that goes wrong with your device**. Incorrect file placement will not brick your device, but reckless behavior might.
* This guide will work on every retail device in the Nintendo 3DS family of consoles (including the New 3DS series and the 2DS), regardless of region or firmware.
* Following this guide alone should not result in data loss, but SD card corruption is always a possibility. You should make a backup of your SD card contents if you have important data.
* You will need a working SD card in your 3DS, as well as the ability to write files to the SD card. The 3DS can read SD cards formatted as MBR/FAT32.

___

!!! tip "" ### Continue to [Get Started](user-guide/get-started.md)
