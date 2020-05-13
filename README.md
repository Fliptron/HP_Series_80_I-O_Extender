# HP_Series_80_I-O_Extender

I/O Extender card for HP Series 80 computers with Logic Analyzer and Oscilloscope probe points.
The PCB is designed to fit within the 100mm x 100mm limit of the El-Cheapo PCB vendors.

The extender plugs into an available I/O slot. It is not wide enough to engage the left
and right sides of the I/O card slot area, and so does not have vertical mechanical
support. To avoid possible damage to th I/O connector, the board should have suitable
support underneath to keep the board level. Holes have been provided on both sides for
either 3D printed or CNC milled supports.

A primary goal was to keep it cheap, and since several Chinese PCB fab companies have
fairly good pricing for small quantities of 2 layer, 100 mm x 100 mm (or smaller)
boards, this design fits within this constraint.

All the pins from the I/O connector are routed to the extender connector with 0.060"
traces (1.5 mm). There is an oscilloscope test point for every signal. There are also
three 10 pin headers (5x2) that are layed out to match the very cheap 8 channel Logic
Analyzers. The choice of signals on these connectors is based on my current project
needs. Obviously, alternative combinations of signals can be achieved by using the
oscilloscope test points.

The Oscilloscope test points and the Logic Analyzers headers are positioned so that
even if the extender is in the top slot, all should be accessable.

After the initial design and fabrication of PCBs, it was noticed that the clock
signals with their 12 volt swin were incompatible with cheap logic analyzers.
The addition of a level shifter installed *dead bug* style has fixed the
problem. The schematic has been updated to reflect the addition, but the gerber
files have not, since no more board fabs are planned.

Detailed description of the Extender board and how to add the level shifter
can be found here [Documentation](http://www.fliptronics.com/HP-85_IO_Extender/index.html)

### Front 3D render

![Front](https://github.com/Fliptron/HP_Series_80_I-O_Extender/blob/master/Front.jpg "Front of Extender Card")

### Back 3D render

![Back](https://github.com/Fliptron/HP_Series_80_I-O_Extender/blob/master/Back.jpg "Back of Extender Card")

