# AnyCubic Kobra Plus Printer Firmware - ShadowFW

This is a modified version of the OEM firmware.

- - - -

### This is part of an optional UI rewrite.
Click the link below for more details on updating the printer UI.<br />
* https://github.com/George-Corrigan/AnyCubic-Kobra-Plus-Max-UI-ShadowUI

- - - -

Below is a list of versions and changes made:

#### v1.0
* Changed auto-leving and probing settings:
   * Increased the probing grid from 5x5 to 7x7
   * Increased the probes from 2 to 3
   * Increased the temp from 190/60 to 200/70
* Change startup beeps to a single beep.
* Changed z-offset step increment from 0.05 to 0.01
* Enabled linear advance support
* Increased the filament unload speed (by 100%)
* Increased the homing speed (by 50%)

- - - -

## Installing ShadowFW printer firmware

1. Download the latest release.

2. Locate the “firmware.bin” file copy to the root of a blank SD card.

3. Turn off the printer and insert the SD card in the printer (upside down, with the metal contacts up).

4. Turn on the printer and wait the a series of beeps, then the normal UI will load.

5. Remove the SD card.


## Reverting to original factory printer firmware

Note: This is to go back to factory defaults if you do not wish to continue using ShadowUI.

1. Go to AnyCubic’s website firmware page [https://www.anycubic.com/pages/firmware-software]. Select your printer series on the left. Select your model on the right. You should see latest firmware version and a link to download it.

2. Locate the “firmware.bin” file copy to the root of a blank SD card.

3. Turn off the printer and insert the SD card in the printer (upside down, with the metal contacts up).

4. Turn on the printer and wait the a series of beeps, then the normal UI will load.

5. Remove the SD card.

- - - -

#### Hc32f460kct6 Marlin
