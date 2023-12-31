# Google Photos unlimited backup module
Adds Photos features and unlimited original backup

<a href="https://github.com/cuynu/gphotos-unlimited-zygisk#usage">
<img alt="DEMO" src="https://github.com/cuynu/gphotos-unlimited-zygisk/assets/90895715/ac4b0200-88f2-4082-b8cb-44d7742258e2" width="330" height="330" />
</a>

</p>

<a href="https://github.com/cuynu/gphotos-unlimited-zygisk#usage">
<img alt="DEMO" src="https://github.com/cuynu/gphotos-unlimited-zygisk/assets/90895715/305700fc-79cb-4391-a038-0da186a66759" width="330" height="330" />
</a>

</p>


Current version : **1.1-stable**

## GLOBAL
## DUE TO STUPID 2FA AUTHENTICATION OF GITHUB, WE HAVE MIGRATED ALL PROJECT TO GITLAB, TO RECEIVE NEW UPDATES OR ANY CHANGES IN THE FUTURE, GO TO THIS : [GitLab cuynu/gphotos-unlimited-zygisk](https://gitlab.com/cuynu/gphotos-unlimited-zygisk)


### Donate this project (Not required)

 <p align="left">
    <a href="https://github.com/sponsors/cuynu"><img src="https://img.shields.io/badge/Support%20Project-%E2%9D%A4-%23db61a2.svg?&logo=github&logoColor=white&labelColor=181717&style=flat-square" alt="Badage"></img></a>

### [Переключиться на русский язык](https://github.com/cuynu/gphotos-unlimited-zygisk/wiki/RU)

### [Chuyển ngôn ngữ Tiếng Việt](https://github.com/cuynu/gphotos-unlimited-zygisk/wiki/VI)

# Introduction 
Based from Pixelify GitHub. This module will spoof your device info to Pixel XL on Google apps and Google Photos to get unlimited backup storage at original quality

# Warning !
Module will only works with Zygisk, it will not run with Riru, Shamiko, etc !!

Some modules could break and prevent this module from running, if module does not work, try disable some modules and see

# Usage 
Download module from [release page](https://github.com/cuynu/gphotos-unlimited-zygisk/releases), enable Zygisk then install with Magisk v24.3+ and reboot

- Tested with : ``Magisk v24.3+`` ``Magisk Delta`` ``KernelSU`` (Zygisk)

# Known issues 
- **Some Xiaomi devices with MIUI 14 when this module is active, its will cause Bootloop with SystemUI crash exception**
- When use together with `Magisk-GApps` module, it will conflict and cause lose the ability to backup unlimited at original quality (Still able to backup unlimited at storage saver quality)

# Tested devices 
* Sony Xperia XZ2/XZ2 Compact/XZ2 Premium (Stock/AOSP)
* Sony Xperia XZ3 (Stock/AOSP)
* Realme C3/C11/C55 (Stock/AOSP)
* Xiaomi Redmi Note 11/Redmi K20 Pro/Redmi Note 7/Redmi Note 4X (AOSP)
* Google Pixel 2/3/4XL/6A (Stock)
* Samsung Galaxy S9/S10/S20/A7 2018/A03S (Stock/AOSP Android 10+)
* Nothing Phone (1) with Nothing OS 2.5.1 CBT
* Masstel_X9 (Stock/AOSP)
* LG G7 ThinQ (Stock/AOSP)
* LG G8, G8x ThinQ (Stock/AOSP)
* LG V40, V50, V50s ThinQ (Stock/AOSP)
* Lenovo Legion Y70 (AOSP)
* Tecno Pova 2 (AOSP)
* Xiaomi Qin F21 Pro (AOSP)

# Build zygisk library
`git clone https://github.com/cuynu/gphotos-unlimited-magisk.git`

Import folder zygisk_build to Android Studio or Gradle and build then copy compiled zygisk library to zygisk folder (not zygisk_build)
