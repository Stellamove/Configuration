# Ender-3 V2

## Flashing Firmware

The bootloader which handles flashing new firmware on this board remembers the last filename you used.

Therefore, to flash the compiled firmware binary onto the board you must give the "`firmware.bin`" file on the SD card a unique name like as "`firmware-20211216-130388.bin`", different from the name of the previous firmware file, or you will be greeted with a blank screen on the next boot.

## Updating the Display

To update the graphics and icons on the display:

- Format an SD card using the FAT32 filesystem with 4096 allocation size.
 
  ![sd_format](https://user-images.githubusercontent.com/96027590/146848283-dd7c6ec1-e38c-4c4e-899c-1120a771dc6b.png)

- Turn off the 3D printer (Ender-3 V2).
- Disconnect and disassembly the LCD unit
- Copy the `DWIN_SET` folder to the SD card and insert the card into the slot on the back of the LCD unit.

  ![LCD](https://user-images.githubusercontent.com/96027590/146306658-913ae79b-578b-4deb-abf5-d3c4d366d74c.png)

- Reconnect the LCD to the 3D printer (Ender-3 V2).
- Turn on the 3D printer (Ender-3 V2) and wait for the screen to change from blue to orange.

  ![lcd_orange](https://user-images.githubusercontent.com/96027590/146307063-43e2b135-a925-4527-bb8d-890f9378dfc2.jpg)

- Turn off the 3D printer (Ender-3 V2).
- Remove the SD card from the back of the LCD unit.
- Reassembly the LCD unit.
