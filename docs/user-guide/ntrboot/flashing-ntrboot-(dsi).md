# Flashing ntrboot (DSi)
---

## Required Reading

Before proceeding, ensure you have read all of the information on [ntrboot](ntrboot)

This method requires temporary access to a Nintendo DSi that is compatible with your flashcart. This method uses the flashcart to run the ntrboot flasher `.nds` file on your DSi. This means that your flashcart must support launching `.nds` files on your DSi's version. See the flashcart table on [ntrboot](ntrboot) for more information.

!!! danger "Important"
	Note that in some rare circumstances, it may be possible for the flashing process to **brick** a counterfeit flashcart and render it permanently unusable. This is unlikely, but nevertheless only original listed flashcarts are supported. To reduce the chance of receiving a counterfeit card, it is recommended that you use a reputable site to buy your flashcart (such as [NDS Card](http://www.nds-card.com/))
	
## What You Need

* Your ntrboot compatible flashcart
* Two devices 
    + **The source DSi**: the Nintendo DSi which is compatible with your flashcart
    + **The target 3DS**: the 3DS family device on stock firmware
* The latest release of [ds_ntrboot_flasher](https://github.com/ntrteam/ds_ntrboot_flasher/releases/latest) *(`dsi` flasher; not the standard flasher)*

## Instructions

### Section I - Prep Work

1. Power off **the source DSi**
1. Insert your flashcart's SD card into your computer
1. Copy `ds_ntrboot_flasher_dsi.nds` to your flashcart's SD card
1. Reinsert your flashcart's SD card back into your flashcart
1. Insert your ntrboot compatible DS / DSi flashcart into **the source DSi**

### Section II - Flashing ntrboot

1. Launch `ds_ntrboot_flasher_dsi.nds` on **the source DSi** using your flashcart
1. Press (A) to continue
1. Use (Up) and (Down) to select your flashcart
1. Press (A) to continue
1. Press (A) to "inject ntrboothax"
1. Press (A) to select "RETAIL"
1. Press (A) to continue
1. Select "EXIT"

___

!!! tip ""
	### Continue to [Installing boot9strap (ntrboot)](../installing-boot9strap-(ntrboot))