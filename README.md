# 01-breadboard

Power supply for a breadboard, with a 5 V rail and a 3.3 V rail.

If you want to make one of these for yourself, you can use this design as it is, or alter it and make it better.
The KiCad project files are in this repository, so you can open the design, change it and send it to the board house of your choice.

## Images

Top side:

![01-breadboard, top side](images/top.png)

Bottom side:

![01-breadboard, bottom side](images/bottom.png)

## Design notes

- Power comes in through the barrel jack **J1**.
- **U1** and **U2** are the two voltage regulators (the board is marked 3.3 V and 5 V).
- **C1 to C4** are the input and output capacitors for the regulators.
- **D1** with **R1** is the power indicator LED.
- **J2** and **J3** are the 4-pin headers at the top edge. The row of holes along the edges lines up with a breadboard's power rails.
- Designed in [KiCad](https://www.kicad.org/). The design has no design-rule (DRC) violations.

## Project files

| File | What it is |
|---|---|
| `01-breadboard.kicad_pro` | KiCad project |
| `01-breadboard.kicad_sch` | Schematic |
| `01-breadboard.kicad_pcb` | PCB layout |
| `images/` | Renders of the board used in this README |

## License

Copyright (C) 2019 John Winans
Modifications Copyright (C) 2026 Muhammad Inuwa Muhammad

This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.
You may redistribute and modify this documentation under the terms of the CERN OHL v.1.2.
(http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR
IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable conditions.

If you choose to manufacture products based on this design, please notify the
modifier (see license section 4.2) via inuwamuhammad930@gmail.com

## Credits

This design is a modified version of the original work by John Winans:
https://github.com/johnwinans/2044-breadboard-power

## Author

Muhammad Inuwa Muhammad, inuwamuhammad930@gmail.com
