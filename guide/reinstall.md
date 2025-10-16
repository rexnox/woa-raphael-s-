<img align="right" src="https://github.com/new-WoA-Raphael/woa-raphael/blob/main/media/raphaelbutnotass.png" width="350" alt="Windows 11 running on a Redmi K20 Pro">

# Running Windows on the Redmi K20 Pro Premium

## Reinstalling Windows

### Prerequisites
- [ADB & Fastboot](https://developer.android.com/studio/releases/platform-tools)

- [Modified TWRP](https://github.com/new-WoA-Raphael/woa-raphael/releases/download/Files/modded-twrp-raphael.img)

### Boot into the modified TWRP
> While in fastboot mode, replace `path\to\modded-twrp-raphael.img` with the actual path of the image
```cmd
fastboot boot path\to\modded-twrp-raphael.img
```

#### Formatting the Windows partition
```cmd
adb shell format
```

## [Next step: Reinstalling Windows](/guide/3-install.md)




















  
