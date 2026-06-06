# Custom-Recovery-Builds-for-Messi-RMX3521


```
Device Name : Realme 9 4G
Build Device: messi
Build Alt. Name: RMX3521
Build Date: 05/06/2026
Build Release: Unofficial Beta
Build Branch: 12.1 (R12.1)
Compatibility: Android 12+
```

## Device Info 

 
| Device                  | Realme 9 4G                                          |
| ----------------------- | ---------------------------------------------------------|
| SoC                     | realme SM6225 Snapdragon 680 4G (6 nm)                      |      
| CPU                     | Octa-core (4x2.4 GHz Kryo 265 Gold & 4x1.9 GHz Kryo 265 Silver)  |
| GPU                     | Adreno 610                                             |
| Internal                | 128GB Storage, 6GB / 8GB RAM                 |
| Model                   | RMX3521 (RE54E2L1) |
| Codename                | Messi  |



## How to flash?
Despite being A/B, it has dedicated recovery partition. You can install without using the usual A/B installation process.

1.Download the .img file from the release page.

2. Place the image file inside platform tools folder in your PC.

3.  Now, open CMD inside platform tools folder.
Boot your device in bootloader/fastboot mode.

4. Type in CMD: fastboot flash recovery name-of-recovery.img. It'll flash in current active slot.

5.After flashing is done, type: fastboot reboot recovery.
