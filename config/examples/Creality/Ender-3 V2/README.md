# Ender-3 V2

## Flashing Firmware

The bootloader which handles flashing new firmware on this board remembers the last filename you used.

Therefore, to flash the compiled firmware binary onto the board you must give the "`firmware.bin`" file on the SD card a unique name like as "`firmware-20211216-130388.bin`", different from the name of the previous firmware file, or you will be greeted with a blank screen on the next boot.

## Updating the Display

To update the graphics and icons on the display:

- Format an SD card using the FAT32 filesystem with 4K cluster size.

  ![image](https://user-images.githubusercontent.com/96027590/146306433-553cd0df-80b2-4e4a-9683-b229fd44ee6b.png)

- Power off the machine.
- Copy the `DWIN_SET` folder to the SD card and insert the card into the slot on the back of the display unit.

  ![LCD](https://user-images.githubusercontent.com/96027590/146306658-913ae79b-578b-4deb-abf5-d3c4d366d74c.png)

- Power on the machine and wait for the screen to change from blue to orange.

  ![lcd_orange](https://user-images.githubusercontent.com/96027590/146307063-43e2b135-a925-4527-bb8d-890f9378dfc2.jpg)

- Power off the machine.
- Remove the SD card from the back of the display.
- Power on to confirm a successful flash.
