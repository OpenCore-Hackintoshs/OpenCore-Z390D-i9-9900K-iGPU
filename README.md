# Specifications

```
Gigabyte Z390 D (Bios: F3h)
 - Audio: 
 - Ethernet: Realtek RTL8111
Intel Core i9 9900K
Ram 
USB 3.1 SSD
Intel UHD Graphics 630
```

- OpenCore 0.6.5
- OS: macOS 11.x
- Host: Hackintosh (SMBIOS: iMac19,1)
- Kernel:
- Resolution: 1920x1080 @ 120Hz

## Install

Download and extract the last release EFI.zip to your the root of your EFI partition and update your SMBIOS values.

For minor hardware differences, like processor and GPU, see the full guide:
https://dortania.github.io/OpenCore-Install-Guide/

---

**SMBIOS:** Mac BIOS Info, on hackintosh is about your Mac fake IDs and Serials.
You can use OpenCoreConfigurator to OpenCore 0.6.5 to generate:
https://github.com/ic005k/QtOpenCoreConfig/releases/tag/20210106

## MacOs Kexts

- Lilu
- AppleALC
- NVMeFix
- WhateverGreen
- VirtualSMC
- SMCProcessor
- SMCSuperIO
- RealtekRTL8111

## Running SOs

- Windows 10
- MacOs 11.1