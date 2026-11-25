# LE75HE

LE75HE is a 75-key (15 × 5, all 1U) Hall-effect keyboard in the XD75 form factor, with a three-column navigation cluster in the centre.

- **Keyboard Maintainer**: [leenknegt-eu](https://github.com/leenknegt-eu)
- **Hardware Support**: [leenknegt-eu/LE75HE](https://github.com/leenknegt-eu/LE75HE)
- **MCU**: AT32F405RCT7, 12 MHz HSE, USB high-speed (8 kHz polling)
- **Bootloader**: Factory AT32 DFU bootloader. Enter the bootloader through the following methods:
  - Hold **BOOT** (SW2) while plugging in the keyboard.
  - Press the `SP_BOOT` binding (`Fn` + `'`).
  - Use the web configurator.

## Installation

Copy this directory into a [libhmk](https://github.com/peppapighs/libhmk) checkout and build:

```bash
cp -r firmware/le75he <path-to-libhmk>/keyboards/
```

```bash
cd <path-to-libhmk> && python setup.py -k le75he && pio run
```

## Key Index

Keys are indexed row-major, matching the `HE1`–`HE75` sensor designators on the PCB (`HEn` = key index `n - 1`).

| Row | Key indices |
| --- | ----------- |
| 1   | 0–14        |
| 2   | 15–29       |
| 3   | 30–44       |
| 4   | 45–59       |
| 5   | 60–74       |
