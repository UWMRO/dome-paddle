# Dome Paddle 

## Summary
Replaces the wired dome paddle with an arduino driven wireless paddle. 
Uses a game controller and a single arduino to recieve and connect directly
to the telescopes traditional dome paddle circuitry. We're using an wireless X-Box 360 controller and receiver.

## USB Host Shield Notes
Game controller is supported as part of the [USB Host Shield library](https://github.com/felis/USB_Host_Shield_2.0)

The shield is using SPI for communicating with the MAX3421E USB host controller. It uses the SCK, MISO and MOSI pins via the ICSP on your board.

Note this means that it uses pin 13, 12, 11 on an Arduino Uno, so these pins can not be used for anything else than SPI communication!
