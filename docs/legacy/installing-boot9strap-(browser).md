---
title: Installing boot9strap (Browser)
---

# Installing boot9strap (Browser)
---

## Required Reading

new-browserhax-xl/old-browserhax-xl (when combined with universal-otherapp) is compatible with version 11.14.0 on all 3DS devices with Internet Browser access.

## What You Need

* The latest release of [universal-otherapp](https://github.com/TuxSH/universal-otherapp/releases/latest)
* The latest release of [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller/releases/latest)
* The latest release of [boot9strap](https://github.com/SciresM/boot9strap/releases/latest) *(`boot9strap-1.3.zip`; not the `devkit` file, not the `ntr` file)*
* The latest release of [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest) 

## Instructions

### Section I - Prep Work

1. Power off your device
1. Insert your SD card into your computer
1. Copy `otherapp.bin` to the root of your SD card and rename it to `arm11code.bin`
    - If you do not see the `.bin` extension, do not add it to the end of the filename
1. Copy `boot.firm` and `boot.3dsx` from the Luma3DS `.zip` to the root of your SD card
1. Create a folder named `boot9strap` on the root of your SD card
1. Copy `boot9strap.firm` and `boot9strap.firm.sha` from the boot9strap `.zip` to the `boot9strap` folder on your SD card
1. Copy `SafeB9SInstaller.bin` from the SafeB9SInstaller `.zip` to the root of your SD card
1. Reinsert your SD card into your device
1. Power on your device

### Section II - Launching SafeB9SInstaller

1. Power on your device
1. On the HOME Menu, press the Left and Right shoulder buttons together to open the camera
    - If you are unable to open the camera, open the Internet Browser and manually type the URL instead (`https://zoogie.github.io/web/nbhax`)
1. Tap the QR code button and scan [this QR code](http://api.qrserver.com/v1/create-qr-code/?color=000000&bgcolor=FFFFFF&data=https%3A%2F%2Fzoogie.github.io%2Fweb%2Fnbhax&qzone=1&margin=0&size=400x400&ecc=L)
    - If you get an error, [follow this troubleshooting guide](../troubleshooting.md#a-browser-based-exploit-is-not-working)
1. If the exploit was successful, you will have booted into SafeB9SInstaller

### Section III - Installing boot9strap

1. Wait for all checks to complete
1. When prompted, input the key combo given on the top screen to install boot9strap
1. Once it has completed, press (A) to reboot your device

### Section IV - Configuring Luma3DS

1. Your device should have rebooted into the Luma3DS configuration menu
    - If you get a black screen, [follow this troubleshooting guide](../troubleshooting.md#black-screen-on-sysnand-boot-after-installing-boot9strap)
1. Use the (A) button and the D-Pad to turn on the following:
    - **"Show NAND or user string in System Settings"**
1. Press (Start) to save and reboot

___

!!! tip ""
    ### Continue to [Finalizing Setup](../finalizing-setup.md)
