# macOS on ASUS TUF A15 FA506QM
My personal notes for running macOS on the ASUS TUF A15 FA506QM.

> [!NOTE]
> This guide is a work in progress, in its early stages and is mostly incomplete.

## Project Status

| macOS | Version | Status |
|--|--| -- |
| macOS Sonoma | `14.6` - `latest` | current - `testing` |

**Model Compatibility**

Theoretically speaking, this should also be compatible with the following models, please report back if you have tested it on any of these models.
| Model Number | Status |
|--|--|
| FA506QM | `working` |
| FX506II | `unknown` |
| FX506IV | `unknown` |
| FA506NF | `unknown` |
| FA506ICB | `unknown` |
| FA706QM | `working` |
| FX706II | `unknown` |
| FX706IU | `unknown` |






**Limitations**
-  NVIDIA RTX 3060 Laptop is disabled due to lack of support for macOS.
-  The stock OEM Storage is **not** compatible with macOS.
-  There is no way to control the keyboard backlight as of this moment.

**What works**
- remind me to come back to this later

**Known Issues**
- [#235 ChefsKissInc/NootedRed](https://github.com/ChefKissInc/NootedRed/issues/235)
- Speaker audio is distorted.
- Boot failing 50% of the time. (Seems to be fixed, under investigation)
  
**Potential Improvements**
-  A way to control keyboard backlight hopefully

## Laptop Configuration

| **Specifications** | **Details** |
|--|--|
| **Model** | ASUS TUF A15 FA506QM |
| **CPU** | Ryzen 7 5800H |
| **iGPU** | Radeon RX Vega 8 |
| **dGPU** | NVIDIA RTX 3060 Laptop ⚠️|
| **Display** | 15.6” 1920x1080 IPS 240hz 100% SRGB |
| **Memory*** | 64GB DDR4 3200MHz |
| **Wi-Fi** | Intel® Wi-Fi 6 AX200 |
| **Bluetooth** | Intel® Wi-Fi 6 AX200 |
| **Storage*** | MSI M390 1TB <br> Transcend TS128GMTE110S 128GB |
| **Audio** | Realtek ALC256 |

<sub> * This is not part of the original configuration of the laptop</sub>

BIOS Firmware Version: `310`

<details>
<summary>Original Configuration</summary>
<br>



> [!WARNING]
> The included OEM Storage is **not** compatible with macOS and will result in a Kernel Panic even with the NVMEFix kext. You will need to replace it with a compatible one.

<p align="center">

| **Specifications** | **Details** |
|--|--|
| **Model** | ASUS TUF A15 FA506QM |
| **CPU** | Ryzen 7 5800H |
| **iGPU** | Radeon RX Vega 8 |
| **dGPU** | NVIDIA RTX 3060 Laptop ⚠️|
| **Display** | 15.6” 1920x1080 IPS 240hz 100% SRGB |
| **Memory** | 16GB DDR4 3200MHz |
| **Wi-Fi** | Intel® Wi-Fi 6 AX200 |
| **Bluetooth** | Intel® Wi-Fi 6 AX200 |
| **Storage** | 512gb NVME M.2 SSD ⚠️|
| **Audio** | Realtek ALC256 |

</p>

</details>
