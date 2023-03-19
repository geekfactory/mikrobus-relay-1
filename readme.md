# mikroBUS compatible relay module (single channel)

This is simple but useful relay module compatible with mikroBUS sockets. It was designed using Autodesk EAGLE free edition.

The relay is a G5-LE from Omron rated for 10A and up to 250 VAC. This module includes all the components to drive the coil using digital signals. An LED provides visual feedback when the coil is energized.

The relay module is designed to be activated with a HIGH level from the microcontroller.

For more information about the design of this module please check the following link:

* ![mikroBUS hardware specification](https://download.mikroe.com/documents/standards/mikrobus/mikrobus-standard-specification-v200.pdf)


## Features and hardware details

* G5LE Omron relay can be used to switch AC or DC loads
* Up to 10 A and 250 VAC switching capability
* mikroBUS form factor can fit a wide variety of development boards
* Designed for 5 VDC coil relays (coil is driven with 5 volts)
* G5-LE can be exchanged for other relay with the same footprint
* LED indicator for relay status
* Activation signal hardwired to the CS pin but can be changed to the following pins using solder jumpers:
	* RST
	* PWM
	* INT

## Repository contents

1. __root__ - EAGLE Source files for the board
2. __/documents__ - Additional documentation, datasheets and assembly instructions
3. __/production__ - History of gerber files sent for production
4. __/extras__ - Technical drawings, mounting hardware and related accessories
4. __/firmware__ - Testing or definitive firmware for this board


## Hardware revisions

* 1.0 - First revision
