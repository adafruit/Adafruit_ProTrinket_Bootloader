Trinket Pro Bootloader

by Frank Zhao, for Adafruit Industries

The USBtinyISP protocol is adapted to be used with an ATmega*8P series microcontroller instead, the USB communication is implemented with V-USB, with USBaspLoader code used as a starting point.

The computer will think that the bootloader is a USBtinyISP. Adafruit's VID and PID for the USBtinyISP are being used. Users of avrdude can simply use "-c usbtiny" as a command line option in order to use this bootloader.

The bootloader uses a timeout, similar to Arduino bootloaders.