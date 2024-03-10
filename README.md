# MP10-Mini-Klipper
Klipper Configuration Settings and Printer.conf file for the 2019 Monoprice MP10 Mini

This release is based off of klipper version v0.12.0-100-g600e89ae

In order to flash this on a stock printer a fat32 formated microsd card with the boot label of "U" must contain klipper.bin renamed as update.bin and printed from the touch screen controller.

If you run into flashing issues. The printers logic board can be placed into dfu mode by pulling up resistor 41 to 3v3. Pins 9 & 10 on the unpopulated debug port can be used for this purpuse.

With klipper.elf and STMCubeProgrammer you can use the command `STM32_Programmer_CLI.exe -c port=USB1 -d C:\klipper.elf` to reprogram the controller.
