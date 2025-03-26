# DELL-OptiPlex-3090-Micro-OpenCore-Hackintosh
DELL OptiPlex 3090 Micro (MFF) OpenCore 1.0.4 Hackintosh

<img src="https://github.com/loox-sys/DELL-OptiPlex-3090-Micro-OpenCore-Hackintosh/blob/main/DELL%20OptiPlex%203090%20Micro%20(MFF).png" alt="DELL OptiPlex 3090 Micro" width="600">

### Hardware
- Motherboard: DELL Q470
- Bios Version: 2.23.0 / latest version
- CPU: Intel i5-10500t
- RAM: Crucial 2x16GB DDR4 3200
- SSD: Samsung SSD PM991a TLC M.2 256GB
- iGPU: Intel UHD Graphic 630
- Audio: Realtek ALC256
- Ethernet: Intel I219-LM
- Wireless / BT: Intel AX201
- PSU: DELL 65W


### OpenCore
Link: [OpenCore 1.0.4](https://github.com/acidanthera/opencorepkg/releases)

### OS Version Tested
✅ macOS Big Sur 11.x / 2020

✅ macOS Monterey 12.x / 2021

✅ macOS Ventura 13.x / 2022

✅ macOS Sonoma 14.x / 2023

✅ macOS Sequoia 15.x / 2025

#### macOS Sequoia 15.3.2 has booted successfully. 
There is no working AirportItlwm.kext for macOS Sequoia, so only the itlwm.kext in conjunction with HeliPort helps.

Link: [itlwm.kext](https://github.com/openintelwireless/itlwm/releases) & [HeliPort](https://github.com/OpenIntelWireless/HeliPort)

### Important
Generate the SMBIOS with OpenCore Configurator
