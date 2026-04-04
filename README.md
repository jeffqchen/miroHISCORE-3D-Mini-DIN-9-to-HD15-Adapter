# miroHISCORE 3D Mini DIN 9 to HD15 Adapter

<img width="800" src="https://github.com/user-attachments/assets/efc3dd3c-b2a0-46c7-bc6d-c1d8d1d17249" />


The miroHISCORE 3D line of 3Dfx Voodoo 1 & 2 cards use a proprietary Mini DIN 9 pin connector to route the output signal of the 2D video card to the Voodoo card. This cable is often missing after many decades. Therefore, I've created this adapter board to convert the DIN connector to a standard male VGA port, so an ordinary Voodoo passthrough cable can be used.

## Parts

Main:

- PCB - [Gerber File](https://github.com/jeffqchen/miroHISCORE-3D-Mini-DIN-9-to-HD15-Adapter/blob/main/KiCAD/jlcpcb/production_files/GERBER-miroHISCORE%20Adapter.zip)
- 9 pin Mini DIN Female Recepticle, Through Hole - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Connectors/Mini%20DIN/Female/9%20Pin/info.md)
- VGA Port Full Depth, Male, Right Angle, Through Hole - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Connectors/HD15/Full/Male/info.md)

Accessories:

- Mini DIN 9 Pin Cable, Male Pin, Straight - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Cable/Mini%20DIN/9%20Pin/%20Male/Straight/info.md)
  - Buy one as short as possible. Mine is 1 meter.
- VGA bracket - With the VGA port opening near the middle.
  - (Optional) 3D Printed bracke - [Link](https://github.com/jeffqchen/miroHISCORE-3D-Mini-DIN-9-to-HD15-Adapter/blob/main/3D%20Print/miroHISCORE%203D%20Daughter%20Board%20Bracket.stl)

## Assembly

### PCB Assembly

Populate the PCB with the two ports.

<img src="https://github.com/user-attachments/assets/d1d68154-9f8c-42da-8263-7add35477ac5" width=300> <img src="https://github.com/user-attachments/assets/ac6f9a1d-8600-41f9-80cb-b2952d7f660a" width=300 />

### VGA Bracket

Drill 29mm from center of VGA port, a hole of 11 mm diameter.

<img width="600" src="https://github.com/user-attachments/assets/a97b819c-81b1-4785-ab01-099a2cbe90d5" />

*(The hole in my photo is obviously off)*

#### 3D Printed Bracket

The 3D printed bracket needs to be bent towards the groove with hot air to become usable. 

### Final Assembly

Undo the hex nuts from the VGA port with a 3/16 socket, insert the VGA port through the back of the bracket, and tighten the nuts back on.

## Usage

Connect the daughter board and the miroHISCORE 3D card with the 9 pin Mini DIN cable.

<img width="600" src="https://github.com/user-attachments/assets/ee798a02-99be-4047-b381-002e3aa26cb8" />

Connect the 2D VGA card to the daughter card with a Voodoo passthrough card.

Connect the VGA output of the miroHISCORE 3D card to the display.


--------
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
