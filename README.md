# Space Invaders FRL

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

## License

The files in this repository are licensed under CERN-OHL-P-2.0. See the LICENSE file for more details.