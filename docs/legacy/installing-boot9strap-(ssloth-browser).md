---
title: Installing boot9strap (SSLoth-Browser)
---

# Installing boot9strap (SSLoth-Browser)
---

## Required Reading

SSLoth allows users on version 11.13.0 and below to bypass the browser version check, allowing use of new-browserhax or old-browserhax, which can then be used in conjunction with universal-otherapp.

!!! tip ""
	If you have updated your device to your current version using a cartridge, your Internet Browser will be inaccessible. If this is the case, you will need to update your device to the latest version through System Settings and then follow the method for the latest version.

## What You Need

* The latest release of [universal-otherapp](https://github.com/TuxSH/universal-otherapp/releases/latest)
* The latest release of [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller/releases/latest)
* The latest release of [boot9strap](https://github.com/SciresM/boot9strap/releases/latest) *(`boot9strap-1.3.zip`; not the `devkit` file, not the `ntr` file)*
* The latest release of [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest) 

### Section I - Prep Work

1. Power off your device
1. Insert your SD card into your computer
1. Copy `otherapp.bin` to the root of your SD card and rename it to `arm11code.bin`
	+ If you do not see the `.bin` extension, do not add it to the end of the filename
1. Copy `boot.firm` and `boot.3dsx` from the Luma3DS `.zip` to the root of your SD card
1. Create a folder named `boot9strap` on the root of your SD card
1. Copy `boot9strap.firm` and `boot9strap.firm.sha` from the boot9strap `.zip` to the `boot9strap` folder on your SD card
1. Copy `SafeB9SInstaller.bin` from the SafeB9SInstaller `.zip` to the root of your SD card
1. Reinsert your SD card into your device
1. Power on your device

### Section II - SSLoth
1. Launch the System Settings application
1. Navigate to `Internet Settings` -> `Connection Settings`
1. Click on your network connection slot and navigate to `Change Settings` -> `Next Page (right arrow)` -> `DNS`
1. Set "Auto-Obtain DNS" to "No", then click `Detailed Setup`
1. Set both the Primary DNS and Secondary DNS to `054.038.133.070`
1. Click OK, then click Save
1. When prompted, click "Test" to perform the connection test
	+ The test should succeed
1. Power off your device

### Section III - Launching SafeB9SInstaller
1. Power on your device
1. On the HOME Menu, press the Left and Right shoulder buttons together to open the camera
    + If you are unable to open the camera, open the Internet Browser and manually type the URL instead (`https://zoogie.github.io/web/nbhax/`)
1. Tap the QR code button and scan [this QR code](http://api.qrserver.com/v1/create-qr-code/?color=000000&bgcolor=FFFFFF&data=https%3A%2F%2Fzoogie.github.io%2Fweb%2Fnbhax&qzone=1&margin=0&size=400x400&ecc=L)
	+ If you get an error, [follow this troubleshooting guide](../troubleshooting.md#a-browser-based-exploit-is-not-working)
	+ If the browser prompts an update, it is possible that your ISP is rerouting DNS changes. Try another internet connection, or update your console to the latest version and follow [Installing boot9strap (Browser)](installing-boot9strap-(browser).md).
1. If the exploit was successful, you will have booted into SafeB9SInstaller

### Section IV - Installing boot9strap

1. Wait for all safety checks to complete
1. When prompted, input the key combo given to install boot9strap
1. Once it has completed, press (A) to reboot your device

### Section V - Configuring Luma3DS

1. Your device should have rebooted into the Luma3DS configuration menu
	+ If you get a black screen, [follow this troubleshooting guide](../troubleshooting.md#black-screen-on-sysnand-boot-after-installing-boot9strap)
1. Use the (A) button and the D-Pad to turn on the following:
	+ **"Show NAND or user string in System Settings"**
1. Press (Start) to save and reboot

### Section VI - Restoring default DNS
1. Launch the System Settings application
1. Navigate to `Internet Settings` -> `Connection Settings`
1. Click on your network connection slot and navigate to `Change Settings` -> `Next Page (right arrow)` -> `DNS`
1. Set "Auto-Obtain DNS" to "Yes"
1. Click OK, then click Save
1. When prompted, click "Test" to perform the connection test
	+ The test should succeed
1. Power off your device

___

!!! tip ""
	### Continue to [Finalizing Setup](../finalizing-setup.md)
