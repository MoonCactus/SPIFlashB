SPIFlashB (SPIFlash for Anarduino)
=========

This derivative is based on SPIFlashB from https://github.com/rrobinet/SPIFlashB
I only reduced it and removed some Serial.print in order to spare memory, and added a few features, like a "circular write" for IoT logging devices. The thing is not extremely efficient though (byte streams), and I may optimize it one day.

**Original readme.md follows**

Anarduino miniWireless library for read/write access to SPI flash memory chips by emulating the Lowpowerlab SPIFlash (see https://github.com/LowPowerLab/SPIFlash). 
This works with 256byte/page SPI flash memory such as the 128MBIT S25FL127S SPANION used on Anarduino miniWireless (http://www.anarduino.com) for data storage and wireless programming.

This library is developed to enable wireless programming on Anarduino miniWireless platform.
 

###License
This library is free software; you can redistribute it and/or modify it under the terms of either the GNU General Public License version 2 or the GNU Lesser General Public License version 2.1, both as published by the Free Software Foundation.

This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Lesser General Public License for more details.
