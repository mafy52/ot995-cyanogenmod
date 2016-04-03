# Introduction #
As of the initial Cyanogenmod release, there are _two_ distinct CWM images.

  1. To **backup or restore** official Alcatel firmware releases, or ROMs based on such releases:
    * _cwm\_cocktail\_stock\_20120609.img_
  1. To **install** the Cyanogenmod release:
    * _cwm\_cocktail\_cyanogenmod\_20121019.img_

Choose the right image and download it from the [Downloads](https://code.google.com/p/ot995-cyanogenmod/downloads/list) section.

# Flashing #
  1. Get the right CWM image zip from the Downloads section
  1. Make sure your device is turned off
  1. Hold **power** and **volume down** until the Alcatel splash screen is shown
  1. Wait another second, then release both keys

The device should now have entered _fastboot_ mode. Proceed with the instructions below.

**Windows:**
  * Make sure you have the fastboot driver installed (installable via Windows update on Windows 7)
  * Use the included _flash.bat_ to flash CWM
  * Alternatively you may use _boot.bat_ to boot without flashing

**Linux:**
  * Install the Android SDK (or a package containing _fastboot_)
  * Use _fastboot flash cwm\_cocktail\_xxxx\_yyyymmdd.img_ to flash
  * Use _fastboot boot cwm\_cocktail\_xxxx\_yyyymmdd.img_ to boot without flashing

**Note:** when installing Cyanogenmod, always have the Cyanogenmod CWM recovery **flashed**.