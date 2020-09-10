# Si4735/Si4732 Digital Radio Breakout Board

This is a simple breakout board that you can use for both the Si4735/32 chips by Silicon Labs. This designed was made after the [Si4735 Arduino Library](https://github.com/pu2clr/SI4735) was published, to explore it's functionality without having too much soldering (the Si4735's SSOP-24 package is just 0.65mm pitch!)

Simply solder one chip at a time, and all supporting passive circuitry.

All parts can be sourced cheaply at LCSC.com, except for the main IC.

## Programming

The [Si4735 Arduino Library](https://github.com/pu2clr/SI4735) is used to send commands to the chip, with the microcontroller of your choice. This board has been tested with the ESP32, but any other microcontroller that can safely supply 100mA of current through the 3.3V supply is fine. Minimally connect the RST, SDA, SCLK, 3V3, GND pins to your microcontroller to get started with the examples provided in the library.
