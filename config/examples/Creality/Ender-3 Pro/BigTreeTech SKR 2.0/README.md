# Ender-3 Pro with BTT SKR 2.0 Board

The Configurations files were created based on the stock Ender-3 Pro. And to maintain compatibility with the 4.2.2 board, which is the basic stock board of Ender-3 Pro, DRIVER_TYPE uses TMC2208_STANDALONE and SPEAKER is disabled because BEEPER pin is used for communication with PITTA.

## Flashing Firmware

The bootloader which handles flashing new firmware on this board use "`firmware.bin`" file on the SD card.

## Configurations

Configurations for Ender-3 Pro with the following options enabled:

  - Motherboard: BOARD_BTT_SKR_V2_0_REV_B
  - X, Y, Z, E0 Drivers: TMC2208_STANDALONE (STEP/DIR Mode)
  - No SPEAKER

## Platformio

Changed development platform settings in platformio.ini for correct build.

```
[platformio]

default_envs = BIGTREE_SKR_2
```
