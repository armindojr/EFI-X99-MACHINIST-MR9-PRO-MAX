# Machinist MR9 Pro Max + Intel Xeon E5-2670 v3 + GT 710 1Gb

**Latest working macOS**: 14.7 (Sonoma)
<br>
**Current OpenCore**: 1.0.1

![about-this-mac](https://github.com/armindojr/EFI-X99-MACHINIST-MR9-PRO-MAX/blob/9f5124d5ebb78d8c9bb181678115d03425d8d5d0/Infos/About%20This%20Mac%20-%20Overview.png)

## Complete hardware specs

| Item     |              Description               |
| -------- | :------------------------------------: |
| MB       |         Machinist MR9 Pro Max          |
| CPU      | Intel Xeon E5 2670 v3 (HEDT Haswell-E) |
| Memory   |      32 Gb DDR4 - 2x16Gb 2133 MHz      |
| Storage  |        NVME Fanxiang S660 512Gb        |
| GPU      |    Inno3d NVIDIA GT710 1Gb (GK208)     |
| Ethernet |      Realtek GBe Family (RTL8111)      |
| Wifi     |            Fenvi Wifi6 card            |
| Audio    |             Realtek ALC897             |

## What works

- macOS Sonoma
- Audio
- HDMI/DP
- All USB ports
- All ports mapped correctly (2.0 and 3.0 with back compatibility)
- Ethernet
- Shutdown/Reboot
- Temperature monitoring for cpu and gpu
- DRM content (Widevine, Playready, Fairplay tested)

## What not works

- Wifi

## Not tested yet

- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)

## Kexts used:

- [AppleALC.kext](https://github.com/acidanthera/AppleALC)
- [CpuTscSync.kext](https://github.com/acidanthera/CpuTscSync)
- [Lilu.kext](https://github.com/acidanthera/Lilu)
- [NVMeFix.kext](https://github.com/acidanthera/NVMeFix)
- [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen)

## Geekbench v6 Results:

- [GeekBench CPU](https://browser.geekbench.com/v6/cpu/1505502)
- [GeekBench Open CL](https://browser.geekbench.com/v6/compute/524582)
- [GeekBench Metal](https://browser.geekbench.com/v6/compute/524584)

## Thanks/Credits

- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)
