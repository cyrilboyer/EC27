# ⚠️ WARNING: UNTESTED PROTOTYPE ⚠️

**THIS PROJECT IS CURRENTLY UNTESTED AND HAS NO FIRMWARE. USE AT YOUR OWN RISK.**

# EC27

Open source split Electrostatic Capacitive PCB inspired by the Kyria.

## Introduction

This project is a fork of Cipulot's EC23U, adapted into a split keyboard design with 27 keys per half. It draws inspiration from the Kyria by splitkb.

## Technical information

- Layout: Split keyboard with 27 keys per half
- Compatible switches: EC switches (Topre)
- Microcontroller: STM32F401
- Connector: USB-C
- Firmware compatibility: To be developed (planned QMK with VIA/VIAL support)
- Protection hardware (present on both halves):
  - Fused
  - ESD protection

## Renders and Prototypes

### Render

![PCB Front Render](/Assets/PCB_render_front_left.png)

![PCB Back Render](/Assets/PCB_render_back_right.png)

![PCB Plate Render](/Assets/PCB_render_plate.png)

### Prototypes

No physical prototypes are available at this time. PCBs have been ordered and are awaiting arrival and testing.
This is my third attempt at an EC design. First one was working and had a Katana-esque layout but I did not know how to design a plate so I scrapped it.

I then made a Dactyl-CC design with a 3d printed case with single PCBs that clip onto the case but the feel of the switches seem a bit harder than it should. It was my first Dactyl and I actually didn't like the ergonomics (although I own a Kinesis).

## Acknowledgements

Huge thanks to Cipulot for their many open source repositories, which I forked for this project instead of using my own schematics (I am no professional, I trust his design more than mine). 


## Copyright notice

This project is not endorsed nor sponsored in any way by Topre Corporation, PFU Limited, or splitkb. Any mentioned trademarks or logos are the property of their respective owners.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
