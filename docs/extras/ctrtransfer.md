---
title: CTRtransfer
---

# CTRTransfer
---

## Required Reading

This is add-on section for installing an 11.5.0 CTRTransfer image to your device.

To use the [magnet](https://wikipedia.org/wiki/Magnet_URI_scheme) links on this page, you will need a torrent client like [Deluge](http://dev.deluge-torrent.org/wiki/Download).

Note that if you have any payload files other than `GodMode9.firm` in the `/luma/payloads/` folder on your SD card, holding (Start) on boot will display a "chainloader menu" where you will have to use the D-Pad and the (A) button to select "GodMode9" for these instructions. 

!!! danger "Important"
	You MUST have already installed Luma3DS and boot9strap to use this.
	
	Performing a CTRTransfer may break extended memory mode games (Monster Hunter, Super Smash Bros, Pokemon Sun/Moon) on Old 3DS/2DS devices. If this occurs, you will need to format the device (using TinyFormat or System Settings) to fix the issue.

## What You Need

* The latest release of [GodMode9](https://github.com/d0k3/GodMode9/releases/latest)
* The latest release of [FBI](https://github.com/Steveice10/FBI/releases/latest) *(the`.3dsx` file)*
* The 11.5.0 CTRTransfer image for your device and region     
*(if your device is not from one of these regions, just pick one that matches your device type)*:    
    +    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [New 3DS or 2DS - 11.5.0 - EUR - CTRTransfer](magnet:?xt=urn:btih:465f1048f81e8e5c651ce2a4d9df48fec88d1099&dn=11.5.0-38E_ctrtransfer_n3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)    
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [New 3DS or 2DS - 11.5.0 - JPN - CTRTransfer](magnet:?xt=urn:btih:70f641c9f2a4933a07fac49eb7ad19451c7c8c96&dn=11.5.0-38J_ctrtransfer_n3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)    
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [New 3DS or 2DS - 11.5.0 - KOR - CTRTransfer](magnet:?xt=urn:btih:c9e4de20d30b80032a5dd6f675fecb6d748f71b1&dn=11.5.0-34K_ctrtransfer_n3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)    
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [New 3DS or 2DS - 11.5.0 - USA - CTRTransfer](magnet:?xt=urn:btih:2b0a71a2523328e447938fea7b4c02ebe0b72705&dn=11.5.0-38U_ctrtransfer_n3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)    
~
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [Old 3DS or 2DS - 11.5.0 - EUR - CTRTransfer](magnet:?xt=urn:btih:df0836a731778ab6ffe9a8c658400c782f0225cd&dn=11.5.0-38E_ctrtransfer_o3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)     
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [Old 3DS or 2DS - 11.5.0 - JPN - CTRTransfer](magnet:?xt=urn:btih:d8913b4c0da224e8852fa2f685c41ddbce5310bc&dn=11.5.0-38J_ctrtransfer_o3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)     
	+    <i class="fa fa-magnet" aria-hidden="true" title="This is a magnet link. Use a torrent client to download the file."></i> - [Old 3DS or 2DS - 11.5.0 - USA - CTRTransfer](magnet:?xt=urn:btih:2708089605ca47387fa64e996a699eedd18031e8&dn=11.5.0-38U_ctrtransfer_o3ds.zip&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2Fbt.xxx-tracker.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fmgtracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.si%3A1337%2Fannounce&tr=udp%3A%2F%2Fpublic.popcorn-tracker.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fthetracker.org%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.cypherpunks.ru%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.ds.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.internetwarriors.net%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.mg64.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.open-internet.nl%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.port443.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qt.is%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.vanitycore.co%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-2.msm8916.com%3A6969%2Fannounce)    

## Instructions

### Section I - Prep Work

1. Power off your device
1. Insert your SD card into your computer
1. Create a folder named `3ds` on the root of your SD card if it does not already exist
1. Create a folder named `cias` on the root of your SD card if it does not already exist
1. Copy `GodMode9.firm` from the GodMode9 `.zip` to the `/luma/payloads/` folder on your SD card
1. Copy the `gm9` folder from the GodMode9 `.zip` to the root of your SD card
1. Copy the 11.5.0 CTRTransfer image `.bin` from the CTRTransfer `.zip` to the `/gm9/` folder on your SD card
1. Copy `FBI.3dsx` to the `/3ds/` folder on your SD card
1. Reinsert your SD card into your device

### Section II - CTRTransfer

1. Press and hold (Start), and while holding (Start), power on your device. This will launch GodMode9
1. If you are prompted to create an essential files backup, press (A) to do so, then press (A) to continue once it has completed
1. If you are prompted to fix the RTC date&time, press (A) to do so, then set the date and time, then press (A) to continue
    + Note that, if you had to fix the RTC date and time, you will have to fix the time in the System Settings as well after this guide
1. Navigate to `[0:] SDCARD` -> `gm9`
1. Press (A) on the CTRTransfer `.bin` to select it
1. Select "CTRNAND options..."
1. Select "Transfer image to CTRNAND"
1. If prompted, select "Transfer to SysNAND"
    + This prompt will only appear if you have an EmuNAND
1. Press (A) to unlock SysNAND (lvl1) writing, then input the key combo given
    + This process will take some time
1. Once the transfer has completed, press (A) to continue
1. Press (B) to decline relocking write permissions if prompted
1. Press (B) twice to return to the main menu
1. Press (Home) to bring up the action menu
1. Select "Scripts..."
1. Select "GM9Megascript"
1. Select "Scripts from Plailect's Guide"
1. Select "CTRTransfer Ticket Copy"
1. When prompted, press (A) to proceed
1. Press (A) to continue
1. Press (B) to return to the main menu
1. Select "Exit"
1. Press (A) to relock write permissions if prompted
1. Press (Start) to reboot your device
1. Update your device by going to System Settings, then "Other Settings", then going all the way to the right and using "System Update"
    + Updates while using B9S + Luma (what you have) are safe
    + If this gives you an error, set your DNS settings to "auto"

### Section III - Launching FBI

1. Launch the Download Play application (this [icon](/images/download-play-icon.png))
1. Press (L) + (Down) + (Select) at the same time to open the Rosalina menu
1. Select "Miscellaneous options"
1. Select "Switch the hb. title to the current app."
1. Press (B) to continue
1. Press (B) to return to the Rosalina main menu
1. Press (B) to exit the Rosalina menu
1. Press (Home), then close Download Play
1. Launch the Download Play application
1. Your device should load the Homebrew Launcher

### Section IV - Reinstalling Tickets

!!! tip ""
	If script found no user tickets told you to skip this section, then skip this section

1. Launch FBI from the list of homebrew
1. Navigate to `SD` -> `cias`
1. Return to the SD directory with (B)
1. Select "gm9"
1. Select "out"
1. Select "ctrtransfer_tickets"
1. Do the following process for either the `eshop` folder, `unknown` folder, or both
    + Navigate to the folder
    + Select "\<current directory>"
    + Select "Install and delete all tickets"
    + Wait. The system may appear to freeze, just give it time.
    + Press (A) to confirm
    + Press (B) to decline installing tickets from CDN.
1. Press (Home) to exit FBI

### Section V - Remove CTRTransfer image

1. Press and hold (Start), and while holding (Start), power on your device. This will launch GodMode9
1. Navigate to `[0:] SDCARD` -> `gm9`
1. Press (X) on the CTRTransfer image `.bin` to delete it
1. Press (A) to confirm
1. Press (Start) to reboot your device

___

!!! tip ""
	### Continue to [Finalizing Setup](../finalizing-setup.md)
