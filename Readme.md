Adafruit Pro Trinket Bootloader

This is the code for the Pro Trinket  bootloader. There are two versions, HV (16MHz 5V) and LV (12MHz 3V), adjust Makefile and recompile.

Check the Makefile for fuses, etc. For advanced users only - we do not offer any support for this code!

**Please note: you cannot use the Adafruit USB VID/PID for your own non-Trinket products or projects. Purchase a USB VID for yourself at http://www.usb.org/developers/vendor/**

Written by Frank Zhao for Adafruit Industries, 2013!

This code is heavily derived from USBaspLoader, but also from USBtiny, with USBtinyISP's settings

Copyright (c) 2013,2014 Adafruit Industries All rights reserved.

ProTrinketBoot is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

ProTrinketBoot is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with ProTrinketBoot. If not, see http://www.gnu.org/licenses/.