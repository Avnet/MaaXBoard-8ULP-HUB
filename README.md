# MaaXBoard-8ULP-HUB
![Title](https://github.com/Avnet/MaaXBoard-8ULP-HUB/assets/88205887/3f4c4d19-b7d9-4991-8aae-bd9100a837e2)

Welcome to the information hub for MaaXBoard 8ULP, featuring the [NXP i.MX 8ULP](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8ulp-applications-processor-family:i.MX8ULP) processor to achieve ultra-low power, EdgeLock® secured intelligent edge applications. The i.MX 8ULP family features up to two Arm® Cortex®-A35 running at 800 MHz, an Arm Cortex-M33 core, 3D/2D Graphics Processing Units (GPUs) and a Cadence® Tensilica® Hifi 4 DSP and Fusion DSP for low-power audio/voice and edge AI/ML processing. This repository serves as a central hub for all resources related to MaaXBoard 8ULP. <br />
**Note: Board images can be downloaded from the Releases section** 

[Buy MaaXBoard 8ULP](https://www.avnet.com/wps/portal/us/products/avnet-boards/avnet-board-families/maaxboard/maaxboard-8ulp?family=&nodeClicked=f43a2eb5-ae8c-482c-924c-5932813d1add)

## Table of Contents
- [MaaXBoard-8ULP-HUB](#maaxboard-8ulp-hub)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
    - [Processing](#processing)
    - [Form Factor \& Interfaces](#form-factor--interfaces)
    - [Memory \& Storage](#memory--storage)
    - [Software \& BSP](#software--bsp)
    - [Accessories](#accessories)
  - [Related Repositories](#related-repositories)
  - [Related Blog](#related-blog)
    - [Hackster.io projects](#hacksterio-projects)
  - [Getting Started and Manuals](#getting-started-and-manuals)
    - [Product Brief](#product-brief)
    - [Getting Started Guide](#getting-started-guide)
    - [Development Guides](#development-guides)

## About
MaaXBoard 8ULP is a power efficient, production ready development board in the popular and compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. This [NXP i.MX 8ULP](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8ulp-applications-processor-family:i.MX8ULP) processor-based platform is ideal for development of cost-efficient Edge-AI, Machine Learning, Secure Entry Access-Control Systems, Inventory and Asset Monitoring applications and many more.<br />
<p align="center">
    MaaXBoard 8ULP is also AWS certified.<br />
    <img src="https://github.com/Avnet/MaaXBoard-8ULP-HUB/assets/88205887/6d043334-183d-4f79-a8f8-e6214778eb92">
<br />
<details>
    <summary>More information & Specs</summary>

### Processing
The i.MX 8ULP device is architected with 3 separate processing domains: The application domain includes two Arm® Cortex®-A35 (800 MHz) cores plus 3D/2D GPUs for GUI-enabled Linux applications. The Real Time domain includes an Arm Cortex-M33 (216 MHz) core, plus Fusion DSP (200 MHz) core for low-power audio/voice use cases. 


### Form Factor & Interfaces
<p align="center">
    <img src="https://github.com/Avnet/MaaXBoard-8ULP-HUB/assets/88205887/e0aaaa1f-f415-42d0-ba01-51400da6e6e2" width="500">
</p>
<p align="center">
    <img src="https://github.com/Avnet/MaaXBoard-8ULP-HUB/assets/88205887/f9aa75dc-843f-49c1-8d9b-944874a1c88d" width="300">
</p>
MaaXBoard 8ULP is engineered as two PCBs, a small SOM (43mm x 36mm) connected via 2x100-pin connectors to a baseboard (BB) in compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. These include Gigabit Ethernet, two USB 2.0 host interfaces, plus separate USB 2.0 device interface, MIPI DSI display and MIPI CSI camera interfaces, a Pi-HAT compatible 40-pin header, MikroE Click 16-pin header plus ADC/DAC 6-pin header.

Audio applications are supported via onboard audio codec, digital microphone and stereo headphone jack I/O. Power is sourced via a USB-C connector and is managed via NXP's PCA9460B PMIC on the SOM plus three additional voltage regulators.

A unique aspect of this board is it’s debug subsystem which supports remote USB access to three UARTs, 16bit I/O expander-based remote control and monitoring, plus integrated SWD/JTAG (or external header) debugger interface.

The back of the board has an M.2 module connector for easy addition of 801.11ac Wi-Fi and Bluetooth 5.1 wireless connectivity.
<p align="center">
    <img src="https://github.com/Avnet/MaaXBoard-8ULP-HUB/assets/88205887/89c67b3b-8731-4253-9f11-680ab61a5da8" width="500">
</p>

### Memory & Storage

The 8ULP processor has on-chip shared RAM (768 KB), while the board is well resourced with power-efficient 32bit wide LPDDR4X DDR (2GB), Octal PSRAM (8 MB), plus eMMC 5.1 flash (32 GB) and Octal SPI NOR flash (4 MB) memory devices.

### Software & BSP
Comming soon.

### Accessories
Available accessory options include a [MIPI 7-inch display](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-disp2-3074457345648625681/), [MIPI CSI camera](https://www.arducam.com/product/arducam-5mp-mipi-camera-for-rzboard-v2l-with-renesas-rz-v2l-processor/), [MaaxBoard 8ULP SOM](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-maaxb-8ulp-som-g-3074457345648110714/) and [5V/3A USB Type C power supply](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-pwrul-3074457345642357173/).

[View other Avnet boards](https://www.avnet.com/wps/portal/us/products/avnet-boards/)
</details>


## Related Repositories
- [MaaXBoard Metalayer](https://github.com/Avnet/meta-maaxboard): Contains the Yocto metalayer for MaaXBoards including MaaXBoard 8ULP as well as **building information**
- [U-boot source code](https://github.com/Avnet/uboot-imx): Contains the source code for U-Boot, a boot loader for Embedded boards.
- [Linux kernel source code](https://github.com/Avnet/linux-imx): Contains the source code for the Linux kernel.
- [imx-mkimage source code](https://github.com/Avnet/imx-mkimage): i.MX Mkimage Bootloader Tool for Yocto and Android.
- [imx-atf source code](https://github.com/Avnet/imx-atf): Trusted Firmware-A (TF-A) is a reference implementation of secure world software for Arm A-Profile architectures.


## Related Blog 
### Hackster.io projects
[Search hackster.io for all MaaXBoard 8ULP projects](https://www.hackster.io/search?q="MaaXBoard%208ULP"&i=projects)

| Topic | Description | Difficulty |
| -- | -- | -- |
| [Connect to AWS IoT Core with Avnet's MaaXBoard 8ULP SBC](https://www.hackster.io/bwilless/connect-to-aws-iot-core-with-avnet-s-maaxboard-8ulp-sbc-b84597) | Getting started guide for connecting an Avnet MaaXBoard 8ULP SBC to AWS IoT Core. | Advanced |
| [Adding Remote Desktop to MaaXBoard 8ULP](https://www.hackster.io/jacob34/adding-remote-desktop-to-maaxboard-8ulp-18d5a4) | Adding remote desktop capability to the MaaXBoard 8ULP using FreeRDP. | Intermediate |

## Getting Started and Manuals
### Product Brief
- [Block Diagram](https://www.avnet.com/wps/wcm/connect/onesite/539f49d6-7ce2-424d-9044-225cce450cd1/P22_875_MaaXBoard_8ULP_block_diagram.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-539f49d6-7ce2-424d-9044-225cce450cd1-o5EV-WU)
- [Product Brief](https://www.avnet.com/wps/wcm/connect/onesite/be32218d-f853-49cf-83f8-f48f446369cc/FY23_1099_MaaXBoard_8ULP_Product_Brief_al_r3.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-be32218d-f853-49cf-83f8-f48f446369cc-oqFmjoC)
### Getting Started Guide
- [Yocto User Manual](https://www.avnet.com/wps/wcm/connect/onesite/07e9ad99-8969-40c1-b632-db97adf350d0/MaaXBoard-8ULP-Linux-Yocto-UserManual-V3.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-07e9ad99-8969-40c1-b632-db97adf350d0-oFe7oZb)
### Development Guides
- [Yocto Development Guide](https://www.avnet.com/wps/wcm/connect/onesite/4fa62a19-239c-40c9-aff6-8a122f993f1e/MaaXBoard-8ULP-Linux-Yocto-Development-Guide-V3.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-4fa62a19-239c-40c9-aff6-8a122f993f1e-oFe7g.T)
