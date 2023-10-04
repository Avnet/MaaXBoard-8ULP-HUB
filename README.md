# MaaXBoard-8ULP-HUB
![Title](https://github.com/MaximSaka/MaaXBoard-8ULP-HUB/assets/88205887/ec10e34a-c6c1-4711-a8af-7398a6cae067)

Welcome to the information hub for MaaXBoard 8ULP, featuring the [NXP i.MX 8ULP](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8ulp-applications-processor-family:i.MX8ULP) processor to achieve ultra-low power, EdgeLock® secured intelligent edge applications. The i.MX 8ULP family features up to two Arm® Cortex®-A35 running at 800 MHz, an Arm Cortex-M33 core, 3D/2D Graphics Processing Units (GPUs) and a Cadence® Tensilica® Hifi 4 DSP and Fusion DSP for low-power audio/voice and edge AI/ML processing. This repository serves as a central hub for all resources related to MaaXBoard 8ULP.

[Buy the MaaXBoard 8ULP](https://www.avnet.com/wps/portal/us/products/avnet-boards/avnet-board-families/maaxboard/maaxboard-8ulp?family=&nodeClicked=f43a2eb5-ae8c-482c-924c-5932813d1add)

## Table of Contents
- [About](#about)
- [Related Repositories](#related-repositories)
- [Related Blog Posts](#related-blog-posts)
- [Getting Started & Manuals](#getting-started-and-manuals)

## About
MaaXBoard 8ULP is a power efficient, production ready development board in the popular and compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. This [NXP i.MX 8ULP](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8ulp-applications-processor-family:i.MX8ULP) processor-based platform is ideal for development of cost-efficient Edge-AI, Machine Learning, Secure Entry Access-Control Systems, Inventory and Asset Monitoring applications and many more.<br />
<p align="center">
    The MaaXBoard 8ULP is also AWS certified.<br />
    <img src="https://github.com/MaximSaka/MaaXBoard-8ULP-HUB/assets/88205887/a83bb35f-21bb-4511-912d-f3cdc47a9bae">
<br />
<details>
    <summary>More information & Specs</summary>

### Processing
The i.MX 8ULP device is architected with 3 separate processing domains: The application domain includes two Arm® Cortex®-A35 (800 MHz) cores plus 3D/2D GPUs for GUI-enabled Linux applications. The Real Time domain includes an Arm Cortex-M33 (216 MHz) core, plus Fusion DSP (200 MHz) core for low-power audio/voice use cases. 


### Form Factor & Interfaces
<p align="center">
    <img src="https://github.com/MaximSaka/MaaXBoard-8ULP-HUB/assets/88205887/df56f9be-9b11-4247-b49b-72be39fc498f" width="500">
</p>

MaaXBoard 8ULP is engineered as two PCBs, a small SOM (43mm x 36mm) connected via 2x100-pin connectors to a baseboard (BB) in compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. These include Gigabit Ethernet, two USB 2.0 host interfaces, plus separate USB 2.0 device interface, MIPI DSI display and MIPI CSI camera interfaces, a Pi-HAT compatible 40-pin header, MikroE Click 16-pin header plus ADC/DAC 6-pin header.

Audio applications are supported via onboard audio codec, digital microphone and stereo headphone jack I/O. Power is sourced via a USB-C connector and is managed via NXP's PCA9460B PMIC on the SOM plus three additional voltage regulators.

A unique aspect of this board is it’s debug subsystem which supports remote USB access to three UARTs, 16bit I/O expander-based remote control and monitoring, plus integrated SWD/JTAG (or external header) debugger interface.

The back of the board has an M.2 module connector for easy addition of 801.11ac Wi-Fi and Bluetooth 5.1 wireless connectivity.
<p align="center">
    <img src="https://github.com/MaximSaka/MaaXBoard-8ULP-HUB/assets/88205887/8bf5d33d-755d-41b0-b149-216046fd1276" width="500">
</p>

### Memory & Storage

The 8ULP processor has on-chip shared RAM (768 KB), while the board is well resourced with power-efficient 32bit wide LPDDR4X DDR (2GB), Octal PSRAM (8 MB), plus eMMC 5.1 flash (32 GB) and Octal SPI NOR flash (4 MB) memory devices.

### Software & BSP
ADD DETAILS HERE !!!!!!!!!!!!!!!!!!!!!!

### Accessories
Available accessory options include a [MIPI 7-inch display](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-disp2-3074457345648625681/), [MIPI CSI camera](https://www.arducam.com/product/arducam-5mp-mipi-camera-for-rzboard-v2l-with-renesas-rz-v2l-processor/), [MaaxBoard 8ULP SOM](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-maaxb-8ulp-som-g-3074457345648110714/) and [5V/3A USB Type C power supply](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-pwrul-3074457345642357173/).

[View other Avnet boards](https://www.avnet.com/wps/portal/us/products/avnet-boards/)
</details>


## Related Repositories
- [MaaXBoard Metalayer](https://github.com/Avnet/meta-maaxboard): Contains the Yocto metalayer for MaaXBoards including the MaaXBoard 8ULP as well as **building information**


## Related Blog Posts
