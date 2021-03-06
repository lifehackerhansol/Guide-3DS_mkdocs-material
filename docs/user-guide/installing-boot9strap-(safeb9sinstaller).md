---
title: Installing boot9strap (SafeB9SInstaller)
---

# Installing boot9strap (SafeB9SInstaller)
---

###Instructions

### Section I - Launching SafeB9SInstaller

1. Launch udsploit from the list of homebrew
1. Once you see `patching kernel... done`, press (Start) to exit udsploit
	+ This may take several tries
	+ If it freezes, just force the console to power off by holding the power button, then try again
1. Launch safehax from the list of homebrew
	+ If you get a "PM INIT FAILED" error, make sure you ran udsploit with Wireless Communication turned on
	+ If you *still* get a "PM INIT FAILED" error, try using the [r19 release of safehax](https://github.com/TiniVi/safehax/releases/tag/r19)
	+ If it freezes, just force the console to power off by holding the power button, then try again
1. If the exploit was successful, you will have booted into SafeB9SInstaller

### Section II - Installing boot9strap

1. Wait for all safety checks to complete
1. When prompted, input the key combo given to install boot9strap
1. Once it has completed, press (A) to reboot your device

### Section III - Configuring Luma3DS

1. Your device should have rebooted into the Luma3DS configuration menu
	+ If you get a black screen, [follow this troubleshooting guide](../troubleshooting.md#black-screen-on-sysnand-boot-after-installing-boot9strap)
1. Use the (A) button and the D-Pad to turn on the following:
	+ **"Show NAND or user string in System Settings"**
1. Press (Start) to save and reboot
	+ If you get an error, just continue the next page

___

!!! tip ""
	### Continue to [Finalizing Setup](../finalizing-setup.md)
