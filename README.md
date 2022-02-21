# C64-RF-Modulator

This is a project of a modulator replacement based on an analog c0pperdragon module. It was adjusted in size to the Commodore C64C motherboard and extended with S-Video and Strereo Audio outputs.

![](images/pcb-c64c-v1.2.png)

### Changelog:

1.2
- internal audio route to left and/or right channel
- ferrite beads to suppresses high-frequency electronic noise
- silkscreen layer with descriptions of all outputs and elements
- 3D models for a nice rendering
- project cleaned up and migrated to KiCad 6.0

1.1
- prototype fixes

1.0
- PCB size adjusted to C64C motherboards (ASSY No.250469)
- S-Video connector added (mini-DIN 4)
- added standard stereo audio mini-jack 3.5mm output

### Prototype images:

The board connected to SixtyClone. Image from S-Video output:

<p align="center">
<img src="https://raw.githubusercontent.com/pmandes/C64-RF-Modulator/main/images/c64c-mount.jpg" height="240">
<img src="https://raw.githubusercontent.com/pmandes/C64-RF-Modulator/main/images/c64c-basic.jpg" height="240">
</p>

The board can be soldered with pins to the motherboard. Then the S-Video and Audio outputs will be at the level of the corresponding openings in the housing.

<p align="center">
<img src="https://raw.githubusercontent.com/pmandes/C64-RF-Modulator/main/images/c64c-back.jpg" height="240">
<img src="https://raw.githubusercontent.com/pmandes/C64-RF-Modulator/main/images/c64c-soldered.jpg" height="240">
</p>

### Links:
- c0pperdragon analog module: https://github.com/c0pperdragon/C64-Video-Enhancement/tree/master/analog_only

