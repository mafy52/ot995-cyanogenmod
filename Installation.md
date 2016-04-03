# Warning #

Cyanogenmod for OT-995 is a work in progress. As such these instructions are meant for **advanced users only**. If you are new to flashing/recovering your device, do **not** attempt to install Cyanogenmod at this time.

<font color='red'><b>Disclaimer:</b> while it should be impossible to brick your device when following these instructions to the letter, you agree being solely responsible for the results of carrying out the instructions outlined in this guide. **Make sure you know how to restore stock firmare before continuing.</font>**

# Introduction #
Make sure you have downloaded the following files:

  * The [latest release of Cyanogenmod](https://code.google.com/p/ot995-cyanogenmod/downloads/list) for OT-995: _cm-10-yyyymmdd-UNOFFICIAL-cocktail.zip_
  * A recent version of [Google Apps](http://wiki.rootzwiki.com/Google_Apps#Jelly_Bean_.28Android_4.1.x.29): _gapps-jb-yyyymmdd-signed.zip_

Store both files on your SD card.

**Backup your current ROM before proceeding.**

(Use the _stock_ CWM image to do so - see below)

# Installing #

## CWM recovery ##

Ensure you have flashed _CWM recovery for Cyanogenmod_.

**Hint:** refer to [FlashingRecovery](FlashingRecovery.md) for instructions on flashing CWM recovery

**Very important:** as of the Cyanogenmod release, there are _two_ distinct CWM images.

  1. To **backup or restore** official Alcatel firmware releases, or ROMs based on such releases:
    * _cwm\_cocktail\_stock\_20120609.img_
  1. To **install** this Cyanogenmod release:
    * _cwm\_cocktail\_cyanogenmod\_20121019.img_

**Notes:**
  * <font color='red'><b>Performing full backups/restores using the Cyanogenmod CWM image is <i>not supported</i></b></font>
  * Selectively backuping/restoring _/data_ should work

## Cyanogenmod ##
  1. Boot to recovery: hold down **power** and **volume up**, release ~2s after the Alcatel splash screen is shown.
  1. If this is _not_ an upgrade, use _"wipe data/factory reset"_ to clear _/data_
  1. Select _"install zip from sdcard"_
  1. Select _"choose zip from sdcard"_
  1. Select "_cm-10-YYYYMMDD-UNOFFICIAL-cocktail.zip_
  1. Select _"Yes - Install_
  1. Wait for _"Install from sdcard complete"_

## Google Apps ##

  1. Select _"choose zip from sdcard"_
  1. Select _"gapps-jb-YYYYMMDD-signed.zip"_
  1. Select _"Yes - install"_
  1. Wait for _"Install from sdcard complete"_
  1. Press the **back** button
  1. Select _"reboot system now"_

# Restoring stock firmware #
  1. Boot or flash _cwm\_cocktail\_stock\_20120609.img_ using fastboot
  1. Select _"Backup and Restore"_
  1. Choose _"Restore"_
  1. Select the backup you made earlier
  1. Reboot