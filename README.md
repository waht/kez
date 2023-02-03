# KEZ


[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

![KEZ](pics/front.jpg)

A 3D printed, handwired, wireless keyboard with 35 keys and a center rotary encoder.

- The case is based on [QEZ](https://github.com/kb-elmo/QEZ) by kb-elmo
- Wireless thanks to [nice!nano](https://nicekeyboards.com/nice-nano)
- [ZMK Firmware](https://github.com/waht/kez_zmk_firmware/)
- Optional RGB underglow

## BOM / Parts

| Part      | Quantity | Notes| 
| :-------------- | :---: | :------ |
|nice!nano v2|1|Other Pro-Micro compatible MCUs should work but might not fit in the case|
|MX Switches|35|
|2u Plate Mounted Stabilizers|2|Optional
|1N4148 Diodes|36|One for every switch plus one for the encoder push switch
|EC11 Rotary Encoder|1|
|16-17mm Knob|1|For rotary encoder
|LiPo Battery|1|Optional. Recommended dimensions: 48 x 22 x 6mm
|Wire||For wiring the circuit
|SK6812 Mini-E|3-4|Optional RGB LEDs for underglow
|Foam Rubber Strips|8| Gaskets for the plate: 50 x 3.5mm - 4 with 2mm height for bottom case & 4 with 1.5 mm height for top case
|M2x4mm|4|Screws for holding top and bottom part together

### 3D Printed Parts

| Part      | Quantity | Notes| 
| :-------------- | :---: | :------ |
|Case Top|1|
|Case Bottom|1|Choose a different color from top or print transparent for RGB underglow
|Case Plate|1|
|MX Switch Sockets|35|Optional but highly recommended, see https://github.com/wlard/keyboards/tree/main/hotswap_socket
|SK6812 Mini-E Sockets|3-4|Optional but recommended, see https://www.printables.com/de/model/380698-sk6812-mini-e-socket

## Building

1. Print the parts
1. If using the switch sockets, add wires and diodes to sockets
1. Put switches into the plate (connect to sockets)
1. [Wire the matrix](/pics/matrix.png) - [Guide](https://github.com/samhocevar-forks/qmk-firmware/blob/master/docs/hand_wire.md#wiring-the-matrix)
1. Add LEDs to bottom (recommended arrangements are one left, one right, one center or two left and two on the right)
1. Mount encoder to top
1. Add foam strips to top and bottom case
1. Slide nice!nano into bottom case (and add battery)
1. Put plate on bottom case
1. Add top case and screws

---

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
