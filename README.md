
# HP ProDesk 400 G6 Mini – Hackintosh

macOS Sequoia running on the HP ProDesk 400 G6 Mini.

This repository contains my OpenCore EFI configuration for running macOS Sequoia on this hardware.

> [!IMPORTANT]
> **DisplayPort required**
>
> The configuration has been tested with a monitor connected via DisplayPort. HDMI is not guaranteed to work.

## Hardware

| Component | Specification |
|---|---|
| Model | HP ProDesk 400 G6 Mini |
| CPU | Intel Core i5-10500T |
| GPU | Intel UHD Graphics 630 |
| Architecture | Intel Comet Lake |
| Form Factor | Mini PC |
| macOS | Sequoia |
| Bootloader | OpenCore |
| Display Output | DisplayPort (tested) |

## Compatibility

| Feature | Status |
|---|---|
| macOS Boot | Working |
| Intel UHD 630 Graphics Acceleration | Working |
| DisplayPort | Working |
| HDMI | Untested |
| Audio | Not confirmed |
| Wi-Fi / Bluetooth | Not confirmed |
| Ethernet | Not confirmed |
| Sleep / Wake | Not confirmed |

## Installation

1. Download the EFI folder from this repository.
2. Configure your own SMBIOS and serial numbers.
3. Mount your EFI partition.
4. Copy the EFI folder to your EFI partition.
5. Boot using OpenCore.

**Important:** Never use someone else's SMBIOS serial numbers.

## Disclaimer

This project is provided **AS IS**, without any warranty or guarantee of functionality.

- Use at your own risk.
- I am not responsible for damaged hardware, data loss, or software issues.
- Compatibility may vary depending on hardware revisions and BIOS settings.
- This configuration is intended for the hardware listed above.

## Credits

- [Acidanthera](https://github.com/acidanthera) – OpenCore, Lilu and WhateverGreen
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/) – OpenCore Installation Guide
- [perez987](https://github.com/perez987/Intel-UHD-630-on-macOS) – Intel UHD 630 reference

---

**macOS Sequoia · HP ProDesk 400 G6 Mini · Intel UHD 630**
