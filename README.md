The HV Rescue Shield 2 is a high voltage parallel mode fuse programmer for Atmel AVR microcontrollers.

It currently supports a wide variety of AVR chips, including the 28-pin ATmega48/88/168/328 series, the 20-pin ATtiny2313, and many 8-pin ATtiny devices (such as the ATtiny25/45/85 and ATtiny13A).  A list of supported devices is in progress, but the Rescue Shield supports many more devices than those listed on the wiki.

Update Feb 2011: Version 2.1 is in stock and shipping now!

Assembly Instructions
Arduino Sketch Download
Usage Instructions
Schematics, layout, and bill of materials
Compatible Devices
Support
Features:
Version 2.1 introduces a new and improved 12V switching circuit
Completely open source. Source code, schematics, layout, BOM are available.
Custom 2-layer PCB with silkscreen and soldermask.  No more hacking and modifying perfboards to fit Arduino’s nonstandard pin spacing!
Onboard 12V DC-DC boost converter eliminates the need for an external 12V power supply.
Support for many common families of AVR microcontrollers in DIP packages.
Support for programming the extended fuse (EFUSE) byte.
An interactive mode, where desired fuses can be entered using the Arduino’s serial port.
Separate Ready and Burn indicators.
Works with the original Arduino (NG, Duemilanove, Uno) and the Arduino Mega.
New in release 2.0:
Support for 8-pin ATtiny devices that use High Voltage Serial Programming (HVSP) mode!
Mode selection at startup so you don’t have to recompile the Arduino sketch to change parts.
More reliable HFUSE burning on all HVPP targets.
Numerous minor bug fixes and speed improvements to the code.
Requirements:
A working Arduino (tested with Arduino Uno, Duemilanove and Arduino NG)
A computer with USB and the Arduino IDE installed (tested with Arduino 0021)
A soldering iron and basic electronics assembly skills