# Serial Data Logger #

An Arduino-compatible logger that writes all serial data input on digital pin 0 (RXD) to a micro SD card. Firmware for the Serial Logger is at [https://github.com/JChristensen/serialLogger](https://github.com/JChristensen/serialLogger). A bill of materials is [available on Mouser.com](http://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=75ac867039).

The firmware can be programmed directly with an ICSP programmer or via a bootloader (use the standard Arduino Uno Optiboot bootloader). Before programming this board with an ICSP programmer, ensure that the SD card is removed.

The Serial Logger board can be powered in several ways:
- Via the FTDI header. This is handy if the MCU being logged uses 5V power.
- Via the power jack. Either 5V regulated or 7-12V can be connected to the jack. First ensure that the four-pin PWR SEL header is jumpered to match the input voltage.
- Via the four-pin PWR SEL header. Remove the jumper and connect either 5V regulated or 7-12V to the like-labeled pin. A ground pin is also provided on the PWR SEL header.

### Revision History ###

**16Oct2014 v2.0** -- Custom PC board, initial version.

### CC BY-SA ###
Serial Data Logger by Jack Christensen is licensed under CC BY-SA 4.0, http://creativecommons.org/licenses/by-sa/4.0/

![](https://raw.githubusercontent.com/JChristensen/serialLogger_HW/v2/serial_logger_pcb.jpg)
