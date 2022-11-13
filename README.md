# Space Invaders FRL

![](https://i.imgur.com/EHRvVH2l.jpg)  
Photo by migfernando#2194

## Disclaimer

Basically, the Space Invaders and the individual Space Invader icons belong solely to Taito Corporation, and cannot be included in this repository. 

## Files

### Case

Case files and drawings are in the `case` folder.

The files are designed for CNC machining and include the drawings for ttap callouts and such. For 3D printing, you may need to modify the files.

### Plate

Plate files are in the `plate` folder.

A DXF file is included for machining/laser cutting.

KiCAD files for an FR4 plate are in the `plate/sifrl-plate` folder. Gerber files are in the `plate/sifrl-plate/JLCPCB/gerbers` folder.

Either way, **order 1mm thick plates**.

### PCB

Main PCB files are in the `pcb` folder.

Gerber files are in the `pcb/JLCPCB/gerbers` folder. Assembly files are in `pcb/JLCPCB/assembly folder`.

A 1.6mm thick PCB should be fine. 1.2mm could work.

### Firmware

The keyboard uses [QMK/VIAL](https://get.vial.today/). Firmware file for it is in the `firmware` folder.

QMK source files for the board are in [this repo](https://github.com/ramonimbao/vial-qmk/tree/kb/sifrl/keyboards/ramonimbao/sifrl).

## Daughterboard

The board uses [my own version of the squatterboard](https://github.com/ramonimbao/squatterboard-v1.5). See the repo for more details.

## Parts Needed

| Qty | Part | Notes |
| --- | ---- | ----- |
| 2   | M3x10 Cap Head Screw | For the case |
| 9   | M2.5x6 Button Head Screw | For the plate |
| 2   | M3x6 Cap Head Screw | For the daughterboard
| 1   | 50mm 4-pin JST-SH cable | Longer is better if you want to be able to reassemble it often |

## License

The files in this repository are licensed under CERN-OHL-P-2.0. See the LICENSE file for more details.