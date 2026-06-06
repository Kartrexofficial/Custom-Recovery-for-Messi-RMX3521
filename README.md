# Custom-Recovery-Builds-for-Messi-RMX3521



Device Name : Realme 9 4G
Build Device: messi
Build Alt. Name: RMX3521
Build Date: 05/06/2026
Build Release: Unofficial Beta
Build Branch: 12.1 (R12.1)
Compatibility: Android 12+

## How to flash?
Despite being A/B, it has dedicated recovery partition. You can install without using the usual A/B installation process.

Download the .img file from the release page.
Place the image file inside platform tools folder in your PC.
Now, open CMD inside platform tools folder.
Boot your device in bootloader/fastboot mode.
Type in CMD: fastboot flash recovery name-of-recovery.img. It'll flash in current active slot.
After flashing is done, type: fastboot reboot recovery.
