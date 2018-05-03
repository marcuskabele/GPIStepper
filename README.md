# GPIStepper

This is a python library for driving stepper motors based on gpiozero for the Raspberry Pi. It is written as close as possible to the gpio zero style and uses as much of the concepts and libraries provided by gpiozero as I can. It should fit into the base gpiozero envorinment.

## Prerequisites:
1. Raspberry Pi
2. gpiozero
3. a unipolar stepper with electronics, like 28BYJ-48 with an ULN2003, other steppers and bipolar will follow

## This version:
### Status:
This version is late alpha, early beta. Most decisions are made, the basic functions are defined.
- the big code-block for accelerating/decellerating steppers beyond the save-starting-speed is missing
- code- and functionality-reviews will try to simplify
- the internal variables and function-names may change, to harmonize wording
- the documentation is missing

### Testing:
This library is tested with cheap 4-phase unipolar 28BYJ-48 stepper motors. 2-Phase Bipolar steppers with H-bridges will be implemented and tested for version 1.

## Future versions:
- will add support for hardware-stepper-drivers
- will add support for 3-phase, 3-coil steppers, like floppy or CD motors

## About me:
I program in Python for almost two years only. And this is my first commitment on github. I still develop my style in this area. My coding during the last decades include Web, Web CMS, Communities, Mac SW, iPhone SW, Newton SW, Apple ]\[ SW. Building electronics, remote controlled planes and helis, my own cockpit.
