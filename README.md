# Macropalexis

Macropalexis is a 4 arrow key with a rotary encoder, an OLED Display. And uses QMK firmware

## Features:
- 128x32 OLED Display
- EC11 Rotary encoder for whatever you want
- 4 Keys

## CAD Model:
Everything fits together using 4 M3 screws and heatset inserts.

It has 2 separate printed pieces. The base where the PCB sits, and the top cover.

<img src=assets/Final_product_with_top.png alt="Schematic" width="500"/>
<img src=assets/Final_product_without_top.png alt="Schematic" width="500"/>



## PCB
Here's my PCB! It was made in KiCad.

Schematic :

<img src=assets/schematic.png alt="Schematic" width="300"/>

PCB :

<img src=assets/pcb.png alt="Schematic" width="300"/>

## Firmware Overview
This hackpad uses [QMK](https://qmk.fm/) firmware for everything. 

- the rotary encoder changes volume. press to pause/play
- The 4 keys currently act as arrow key
- The OLED will display the volume and the music

## BOM:
Here should be everything you need to make this hackpad

- 4x Cherry MX Switches
- 4x DSA Keycaps
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm screws
- 1x 0.91" 128x32 OLED Display
- 1x EC11 Rotary Encoder
- 1x XIAO RP2040
