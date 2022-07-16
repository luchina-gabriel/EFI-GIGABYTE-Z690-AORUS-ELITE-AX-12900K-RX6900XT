# Gigabyte Z690 Aorus Elite AX + i9 12900K + RX 6900 XT + Fenvi BCM94360NG

![about-12 3 1](https://user-images.githubusercontent.com/23700365/161353027-9aaeddf5-7457-49a8-b322-4e99ab94c679.png)

**Latest working macOS**: 12.4
<br>
**Current OpenCore**: 0.8.2

## Complete hardware specs
- Intel i9 12900K @ Stock (All cores (P+E+HT) activated)
- Gigabyte Z690 Aorus Elite AX @ BIOS F6a
- RX 6900 XT - Nitro+ Special Edition (Sapphire - PN: PN 11308-03-20G)
- 4x 16Gb DDR4 4133Mhz XPG D50 with XMP Enabled
- Wifi/BT replaced by Fenvi BCM94360NG - Work OOB

## What works
- macOS Big Sur, macOS Catalina and macOS Monterey
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used:
- AppleALC.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- https://browser.geekbench.com/v5/cpu/11647562
- https://browser.geekbench.com/v5/compute/3921810
- https://browser.geekbench.com/v5/compute/3921809

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 11th Intel Gen - Rocket Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-11THGEN-ROCKET-LAKE)
- tonymacx86.com - in special @etorix and @CaseySJ

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
