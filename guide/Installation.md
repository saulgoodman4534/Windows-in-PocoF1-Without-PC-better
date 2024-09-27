# PocoF1 Windows Installation [Without PC]
<img align="right" src="beryllium.png" width="350" alt="Windows installation on beryllium">

## Steps for Installation
- 1st Step - Partitioning
- 2nd Step - Installation
- 3rd Step - Dual Boot
#
### Prerequisites
- A Working Brain (most important of all)

- Unlocked bootloader

- Rooted and Installed Custom Recovery

### [WARNING]
> - All your data will be erased ! Back up now if needed.
> - Backup Important Partition (Boot, EFS, Modem and Persist) and copy it to outside phone memory
> - Your phone must be rooted, if it is not, follow [root](https://github.com/Kumar-Jy/Windows-in-PocoF1-Without-PC/blob/main/guide/root.md) guide before start the process.
> - Do not flash/run the same file/command twice unless specified.
> - Follow step by step guide, don't jump or skip any step.
> - YOU CAN BREAK YOUR DEVICE WITH THE COMMANDS/FILE BELOW IF YOU DO THEM WRONG!!!
> - DO NOT REBOOT YOUR PHONE! If you think you made a mistake, ask for help in the [Telegram chat](https://t.me/WinInstaller).
#

### 1st Step - Partitioning
- Flash [Moded Ofox Recovery](https://github.com/Kumar-Jy/Windows-in-PocoF1-Without-PC/releases/tag/Moded-Ofox-Recovery) either through your existing recovery or extract recovery.img from zip and flash through fastboot.
- Type ` partition $ ` on recovery terminal [Replace $ with the size of storage in GB you want for Windows, Ex. - for 40GB type `partition 40`] (do not add GB at the end.)
- If it asks you to run it once again, do so
- Reboot to check if Android still works. If it doesn't boot, format userdata and Reboot.
- Root it (if not already rooted), Install Magisk/KernalSU
- Download and install the [WOA Helper app](https://github.com/Marius586/WoA-Helper-update/releases/tag/WOA), open it and grant root access.
- #### Notes :- 
> - if your phone encrypted first unmount and format userdata then type above command to create partition.
> - If you already modified or installed Windows, first type ` restore ` then type above command to create new partition. 
#

### 2nd Step - Installation
- Download windows esd image of your choice from [here](https://arkt-7.github.io/woawin/)
- Download [WinInstaller.zip](https://github.com/Kumar-Jy/Windows-in-PocoF1-Without-PC/releases/tag/PocoF1 WinInstaller)
- Reboot to recovery and flash it ( at least 6GB free space in phone memory required for flashing )
- That's all , 
 You don't need to touch you phone just sit back and watch, all installation process start automatically and phone will reboot to windows setup.
- #### Notes :- 
> - Must remove any attached usb device or charger before flashing, or it may be BSOD error.
> - for any installation error visit  [troubleshooting](troubleshooting.md) 

#
### Last Step - Dual Boot Setup
#### Switch to Android
- Run `Android` Icon from windows desktop to boot into Android.
#### Switch to Windows
- Open WOA Helper app (Installed it and grant root access, if not already installed) and press ``QUICKBOOT TO WINDOWS``, it will boot in windows.
 
#### Notes :- 
> - whenever you install new Android Rom, must creat backup of boot.img of newly installed android.
> - for creating backup , open Woa Helper app, graant root access - First tap on ``MOUNT WINDOWS`` then tape on `` BACKUP BOOT IMAGE `` and select ``WINDOWS`` .
#
#  [Troubleshooting](troubleshooting.md) 






















