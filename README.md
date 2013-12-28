rpiledstripper
==============

LED strip control with raspberry pi

This is based on the tutorial available from adafruit: http://learn.adafruit.com/light-painting-with-raspberry-pi

Install
-------

The raspberry pi unit should have the Occidentalis linux distribution (currently based on Raspian Wheezy) installed.
Occidentalis has hardware SPI support which make updating the LEDs much faster.

http://learn.adafruit.com/adafruit-raspberry-pi-educational-linux-distro/overview

Configuration
-------------


Usage & Patterns
--------

The following patterns are available:
* solid (set a color for all LEDs)
* fade (fade through a series of solids)
* chase (colors hop from one LED to the next)
* random (every color is set by a PRNG)
