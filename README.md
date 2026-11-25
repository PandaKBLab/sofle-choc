# PandaKB Sofle Choc

A low-profile split keyboard based on Brian Low’s Sofle Choc. The PandaKB PCB keeps the original Sofle Choc switch plate geometry, PCB outline, and screw-hole positions. The original Sofle Choc plates fit this revision.

The PandaKB PCB adds a QMK handedness resistor option, a battery connector, a power switch, and an ESD protection device for the split interface.

## Firmware

| Setup | Firmware | Availability |
| --- | --- | --- |
| Wired split | QMK | PandaKB build pending verification |
| Wireless split | ZMK | PandaKB build pending verification |

Select the build for your controller and PCB revision before flashing. Verified PandaKB builds, source links and flashing instructions will be listed on the [Releases page](https://github.com/PandaKBLab/sofle-choc/releases).

## Hardware downloads

| File | Download |
| --- | --- |
| Left switch plate | [DXF](hardware/sofle-choc-plate-left.dxf) |
| Right switch plate | [DXF](hardware/sofle-choc-plate-right.dxf) |
| `SofleChoc-V1` bare PCB | [STEP](hardware/sofle-choc-v1-pcb.step) |
| Schematic | Pending a complete schematic for this PCB revision |
| Cases | [Case references](cases/) |

The plate drawings are at 1:1 scale in millimeters. Case designs also need clearance for the controller, power switch, and battery connector.

## Credits

The [original Sofle Choc](https://josefadamcik.github.io/SofleKeyboard/build_guide_choc.html) was designed by Brian Low. It builds on Dane Evans’s Sofle RGB and Josef Adamčík’s Sofle V2. The plate DXFs were exported from the [upstream switch plate drawing](https://github.com/josefadamcik/SofleKeyboard/blob/fb294f7c58d0f91c379a9ef339159d4d056643e9/Sofle_Choc/Case/PCBTop/SofleKeyboardTopPlate.kicad_pcb) and mirrored for the opposite half. See the [upstream license notice](hardware/UPSTREAM-NOTICE.txt).
