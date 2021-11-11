# 32-pin PLCC Plug and Interposer

Ever need to probe the address and data lines of a ROM chip while it is connected in another circuit board? Or maybe you want to build a board to emulate a ROM chip using a microcontroller or something. Here's a solution: a 3D-printable 32-pin PLCC plug that can be paired up with an optional interposer circuit board.

![32-pin PLCC plug and interposer photo](https://github.com/schlae/32plcc-plug/blob/main/32plcc.jpg)

Some of the compatible ROM chips include:

- 27C256
- 27C512
- 27C010
- 48F010
- 27C020
- 39VF010


## The plug

The plug body can easily be printed with a standard FDM printer. I use an Ender 3 with the detail set to low.

After the print, you may need to clear out the holes and widen them slightly with a pushpin. They are sized so that square pins from a 0.1" header will fit into them. If you salvage the pins from a right angle header, you won't even need to worry about bending them.

Be very careful when soldering the plug since the plastic melts very easily. Use a lower temperature setting on your soldering iron, and consider using a low melting point solder such as Chip Quik.

[Plug STL file](https://github.com/schlae/32plcc-plug/blob/main/32plccplug1.STL)

## The interposer board

One way to use this plug is to solder it to an interposer board which makes it easy to probe pin connections with a ROM chip connected in a pass-through arrangement. Of course, you can use it for whatever you want, borrowing the footprint from the interposer board design.

The headers around the edges of the board are designed for standard 0.1" header pins which can be connected to logic analyzer probes.

## License

This work is licensed under a Creative Commons Attribution-ShareAlike 4.0
International License. See [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/).


