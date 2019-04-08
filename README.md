# pdp8life
Conway's Game of Life for the PDP-8

![Screenshot](screenshot.png)

Requires 8k of memory at the moment; one field for the program, and
one field for the bitmap. No operating system is supported yet, though
this plus other features are coming, including VC8E (with and without
a storage oscilloscope).

Assembles fine with `palbart` and should assemble fine with PAL8. 
Starting address is 0200, and be sure you're using a video terminal with
the font set very small (and a square font cell if possible).

Several assemble-time options are available, including many initial
conditions from gliders to guns to fillers and more. The initial conditions
are all based on the standard RLE format, so adding more is very easy.
