<img align="right" src="https://github.com/new-WoA-Raphael/woa-raphael/blob/main/media/raphaelbutnotass.png" width="350" alt="Windows 11 running on a Redmi K20 Pro">

# Running Windows on the Redmi K20 Pro Premium

## Root guide

### Prerequisites
- [Magisk](https://github.com/topjohnwu/Magisk/releases/latest)

- [ADB & Fastboot](https://developer.android.com/studio/releases/platform-tools)

- [Modified TWRP](https://github.com/new-WoA-Raphael/woa-raphael/releases/download/Files/modded-twrp-raphael.img)

### Boot into the modified TWRP
> While in fastboot mode, replace `path\to\modded-twrp-raphael.img` with the actual path of the image
```cmd
fastboot boot path\to\modded-twrp-raphael.img
```

#### Backing up your boot image
> Sometimes flashing Magisk can cause a bootloop. To fix this, you'll need to restore a boot.img backup.

Use the TWRP backup feature to make a backup of the boot partition.

### Flashing Magisk
- Flash the **magisk.apk** (you may have to rename it to magisk.zip) and reboot your phone. 
- Once booted, locate the **Magisk** app and open it.
- Follow any instructions provided. Select the **direct install** method if you are provided with several methods.

Your phone will now reboot, and you have succesfully rooted it.

> [!IMPORTANT]
> After you've rooted your phone, create a new boot.img backup in Android and in Windows (using the WOA Helper app) and remove any remaining boot.img backups you have made previously. If you don't do this, switching to Android will unroot your phone.
> 
> After updating or changing your rom (and rerooting) you will have to repeat all the steps on this page.

## Finished!
