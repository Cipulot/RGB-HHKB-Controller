# RGB HHKB Controller

 HHKB Pro 2 Keyboard Controller Board with RGB strip support.

## Introduction

This project is a continuation of my development of open source EC boards.

It's a derivative of the [Hasu HHKB Controller](https://github.com/tmk/HHKB_controller) with an updated MCU package and RGB strip support.

This board is USB-mode only and is **NOT** compatible with the BLE options.

## Technical information

- Microcontroller: Atmel Atmega32U4
- Connector:
  - USB-C
  - HHKB ANSI connector
  - HHKB JP connector
- Firmware compatibility: QMK (with VIA/VIAL support)
- Protection hardware (on all connection methods):
  - Fused
  - ESD protection
-RGB strip connector, both THT and SMD pad on both sides of the board.

## Renders and Prototypes

### Render

![PCB Front Render](/Assets/PCB_render_front.png)

![PCB Back Render](/Assets/PCB_render_back.png)

### Prototype

TBD

## Revisions and relative features

### Rev1

This revision implements all the main features of the PCB.

The controller is electrically compatible with both the ANSI and JP version of the HHKB keyboard but you will need to chose between the 2 connectors.

#### Connector choice

Pay attention at the time or ordering the PCBs to populate only one of the 2 connectors:

- `S13B-ZR-SM4A-TF` for ANSI
- `DF14A-15P-1.25H` for JP

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
