what to do, for me it's better to download macOS13 and then upgrade to your desired version of macOS, this what i know, i'm new to hackintosh
download the efi file and mac os 13, here i used airport kext file istead of itlwm so you can use wifi with no problem
download the original repo (Rybo713) as zip, format your usb with rufus to non bootable and fat32, and delete the two new rufus files inside it, put your efi inside it, and download the macOS image see this guides

https://www.youtube.com/watch?v=SSP2z_Vg_ew
https://www.youtube.com/watch?v=S7neu7Dprl0

what i found it's better to download macOS 13 and then update to macos 14 , in macos15 i think is a bit heavy on ressource and wait for it to mature, althout it's the before last version of macos intel, is run most of time and that understandable as apple intelligence got introduced, maybe a way to reduce it's ressource impact tweak?

this pc hardware support the macOS26 without OCLP (open core legacy patcher), this version = Tahoe is the final version of macOS that supports Macs with Intel processors
the end of hackintosh on intel computer?

but based on (open core simplify)[https://github.com/lzhoang2801/OpCore-Simplify], the best version for this pc is macos 13

my notes : https://www.notion.so/achma-learning/macOS-2d97c1c315a480c79e65f1352b1cca04

# macOS for ThinkPad X1 Carbon 6th Gen [20KG]
![X1C6](https://psrefstuff.lenovo.com/syspool//Sys/Image/ThinkPad/ThinkPad_X1_Carbon_6th_Gen/ThinkPad_X1_Carbon_6th_Gen_CT1_09.png)

This project is to give the X1C6 a complete and functional build of macOS Ventura `15.1` using the guide from  [here](https://github.com/tylernguyen/x1c6-hackintosh) with modified ACPI and updated kexts.

Using `MacbookPro15,2` SMBIOS

## My Specs
**Model:** X1C6 [20KG]

**Bios:** 1.68 Vanilla

**CPU:** 2.11GHz Intel i7-8650U (0x8086)

**GPU:** Intel UHD620 1536MB (0x5916)

**RAM:** 2133MHz 16GB Dual Channel LPDDR3

**Display:** 14" IPS Anti-Glare FHD Non-Touch, 1920x1080, 60Hz

**Storage:** PCI-E x4 NVMe WD SN730 512GB

**Partition Type:** APFS

**Wifi:** Intel Wireless AX210NGW

**Bluetooth:** Intel Wireless AX210NGW

**Bootloader:** OpenCore vx

## Note
Your laptop may or may not have the exact specs as mine. Results may vary. If you need help, please ask.

## Tested Configurations
- macOS Ventura (13.x)
# Pre-Installation
1. Follow tylernguyen's [guide](https://tylernguyen.github.io/x1c6-hackintosh/).
2. disable secure boot in BIOS and better to change this : [Colton's BIOS Settings](https://github.com/Colton-Ko/macOS-ThinkPad-X1C6#uefi-setup-configuration)
4. Generate SMBIOS for `MacbookPro15,2`

## kext to add
1. AppleBacklightSmoother.kext , (inspiration)[https://github.com/huyhoang8398/x1c7-hackintosh-20R1#display-trackpad-trackpoint-and-keyboard] 

## Credits
- tylernguyen https://github.com/tylernguyen/x1c6-hackintosh
- benbender https://github.com/benbender/x1c6-hackintosh
- zhtengw https://github.com/zhtengw/EFI-for-X1C6-hackintosh
- Colton-Ko https://github.com/Colton-Ko/macOS-ThinkPad-X1C6
- wallpaper credit : https://github.com/anathonous/X1C5-Hackintosh-OpenCore-MacOSX/tree/main/Wallpapers
