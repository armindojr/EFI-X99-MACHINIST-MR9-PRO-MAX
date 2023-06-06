# Machinist PR9 Pro Max + Intel Xeon E5-2670 v3 + RX 5600 XT 6Gb
**Latest working macOS**: 13.4 (Ventura)
<br>
**Current OpenCore**: 0.9.2

![about-this-mac](https://github.com/armindojr/EFI-X99-MACHINIST-PR9-PRO-MAX/blob/ffb56cf1d91fc40a9f17f0588e6b19424eb35890/Infos/About%20This%20Mac%20-%20Overview.png)

## Complete hardware specs
|Item|Description|
|-|:-------:|
|CPU|Intel Xeon E5 2670 v3 (HEDT Haswell-E)|
|Memory|16 Gb DDR4 - 1x16Gb 2133 MHz|
|Storage|NVME Fanxiang S660 1Tb|
|GPU|AMD Radeon RX 5600 XT 6 GB Sapphire Pulse|
|Ethernet|Realtek GBe Family (RTL8111)|
|Audio|Realtek ALC897|

## What works
- macOS Ventura
- Audio
- HDMI/DP
- All USB ports
- Ethernet
- Shutdown/Reboot

## What doesn't work
- All USB ports is mapped to 2.0

## Not tested yet
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything
- DRM content

## Kexts used:
- AppleALC.kext - [version 1.7.5](https://github.com/acidanthera/AppleALC)
- CpuTscSync.kext - [version 1.0.9](https://github.com/acidanthera/CpuTscSync)
- Lilu.kext - [version 1.6.5](https://github.com/acidanthera/Lilu)
- NVMeFix.kext - [version 1.1.0](https://github.com/acidanthera/NVMeFix)
- RealtekRTL8111.kext - [version 2.4.2](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- VirtualSMC.kext - [version 1.3.1](https://github.com/acidanthera/VirtualSMC)
- WhateverGreen.kext - [version 1.6.4](https://github.com/acidanthera/WhateverGreen)

## Geekbench v6 Results:
- [GeekBench CPU](https://browser.geekbench.com/v6/cpu/1505502)
- [GeekBench Open CL](https://browser.geekbench.com/v6/compute/524582)
- [GeekBench Metal](https://browser.geekbench.com/v6/compute/524584)

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)
