---
title: Homebrew Launcher (Soundhax)
---

# Homebrew Launcher (Soundhax)
---

## Required Reading

The Homebrew Launcher has many different entrypoints, or methods of launching.

Soundhax (when combined with the Homebrew Launcher) is compatible with versions 9.0.0 through 11.3.0 in the EUR, JPN, KOR, and USA regions.

Ensure your device's Wireless Communication is turned on as udsploit (used in the next page) will need the wireless module to be active to function, and some devices (New 3DS, New 2DS, and Old 2DS) cannot adjust the Wireless Communication setting from the Homebrew Launcher. Wireless Communication only has to be on; connecting it to an access point is not required.

!!! danger ""
	Note that cartridge updates will only deliver updates to core features, such as the System Settings, Home Menu, etc. cartridge updates will not deliver updates to Nintendo 3DS Sound and Network features, such as System Transfer, Internet Browser, StreetPass Mii Plaza, or eShop.

	This means that using a cartridge update from a version containing an older Nintendo 3DS Sound version *(<2.1.0)* to one that introduced a newer Nintendo 3DS Sound version will break Soundhax! You will need an [alternate method](homebrew-launcher-(alternatives)) of entering the Homebrew Launcher!

## What You Need

* The latest release of [Soundhax](http://soundhax.com) *(for your region, device, and version)*
	+ If Soundhax appears in your browser as an unplayable video, press Ctrl+S or Cmd+S to save it to your computer
* The latest release of [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller/releases/latest)
* The latest release of [boot9strap](https://github.com/SciresM/boot9strap/releases/latest) *(`boot9strap-1.3.zip`; not the `devkit` file, not the `ntr` file)*
* The latest release of [safehax](https://github.com/TiniVi/safehax/releases/latest) *(the `.3dsx` file)*
* The latest release of [udsploit](https://github.com/smealum/udsploit/releases/latest)
* The latest release of [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest)
* The [otherapp payload](https://smealum.github.io/3ds/#otherapp) *(for your region, device, and version)*

## Instructions

1. Power off your device
1. Insert your SD card into your computer
1. Create a folder named `3ds` on the root of your SD card if it does not already exist
1. Copy the Soundhax `.m4a` to the root of your SD card
1. Copy the otherapp payload to the root of your SD card and rename it to `otherapp.bin`
1. Copy `boot.firm` and `boot.3dsx` from the Luma3DS `.zip` to the root of your SD card
1. Create a folder named `boot9strap` on the root of your SD card
1. Copy `boot9strap.firm` and `boot9strap.firm.sha` from the boot9strap `.zip` to the `/boot9strap/` folder on your SD card
1. Copy `safehax.3dsx` to the `/3ds/` folder on your SD card
1. Copy `udsploit.3dsx` to the `/3ds/` folder on your SD card
1. Copy `SafeB9SInstaller.bin` from the SafeB9SInstaller `.zip` to the root of your SD card and rename `SafeB9SInstaller.bin` to `safehaxpayload.bin`

!!! tip ""
    ![](/images/screenshots/boot9strap-hb-file-layout.png)


1. Reinsert your SD card into your device
1. Power on your device
1. Launch Nintendo 3DS Sound

!!! tip ""
    ![Welcome Screen](/images/screenshots/soundhax-welcome.png)

1. If you've never opened Nintendo 3DS Sound before and get tips on how to use it from a bird icon, go through all of the bird tips, then close the app normally and relaunch it
	+ In this situation, launching Soundhax immediately would cause these tips to appear on every launch of the Nintendo 3DS Sound until this is done
1. Go to `/SDCARD`, then play "<3 nedwill 2016"
	+ This may take many tries
	+ If it freezes, just force the console to power off by holding the power button, then try again
	+ If you get a red screen, ensure you copied `boot.3dsx` (the Homebrew Launcher) to the root of your SD card

!!! tip ""
	![Launching Soundhax](/images/screenshots/soundhax-launch.png)

1. If the exploit was successful, your device will have loaded the Homebrew Launcher

!!! tip ""
    ![Homebrew Launcher](/images/screenshots/homebrew-launcher.png)
___

!!! tip ""
	### Continue to [Installing boot9strap (SafeB9SInstaller)](installing-boot9strap-(safeb9sinstaller).md)
