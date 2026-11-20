# XD75HE

XD75HE is a 60% Hall-effect keyboard PCB with 8kHz polling rate designed in the layout of the KPRepublic XD75RE.

## Features

- Top-, bottom- and gasket-mount cases, see below for supported cases
- [libhmk](https://github.com/peppapighs/libhmk) firmware.
- [hmkconf](https://hmk.prasertsuk.com) web-based configurator.

## Disclaimer

- Work in progress. Do not attempt to fabricate yet.

## Layout
The labels are only an example, keys can be where you want.
<img width="830" height="290" alt="image" src="https://github.com/user-attachments/assets/045c6635-e134-48ce-9ada-97ede8cd68b2" />



You may change the Hall-effect sensors during the component selection based on your preference, and availability. Different sensors require different calibration values, which can be adjusted using the web-based configurator. Here are some options that I have used:

- GH39FKSW (Cheapest)
- MT9102ET
- SS39ET
- DRV5055A3
- OH49E-S (Discontinued)

The fabrication files above are available under releases.

## Case
Currently the only plate made is for the [kbdfansGT-60](https://kbdfans.com/collections/gt-60) case. Other gasket and top mount cases *might* use the same mounting, but I am not sure.

Plate fabrication files can be found in the folder named after the compatible case.

## Firmware
Firmware is not yet made, but will use libhmk.

Head to [libhmk](https://github.com/peppapighs/libhmk/releases) for a pre-compiled firmware. The firmware can be flashed using DFU mode, which can be entered by holding the BOOT button before plugging in. You may need to install the DFU bootloader driver using Zadig. See [libhmk](https://github.com/peppapighs/libhmk) for more information for firmware flashing instructions.
