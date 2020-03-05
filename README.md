# HP_Series_80_I-O_Extender
I/O Extender card for HP Series 80 computers with Logic Analyzer and Oscilloscope probe points.
The PCB is designed to fit within the 100mm x 100mm limit of the El-Cheapo PCB vendors.

The extender plugs into an available I/O slot. It is not wide enough to engage the left
and right sides of the I/O card slot area, and so does not have vertical mechanical
support. To avoid possible damage to th I/O connector, the board should have suitable
support underneath to keep the board level.

A primary goal was to keep it cheap, and since several Chinese PCB fab companies have
fairly good pricing for small quantities of 2 layer, 100 mm x 100 mm (or smaller)
boards, this design fits within this requirement.

All the pins from the I/O connector are routed to the extender connector with 0.060"
traces (1.5 mm). There is an oscilloscope test point for every signal. There are also
three 10 pin headers (5x2) that are layed out to match the very cheap 8 channel logic
analyzers. The choice of signals on these connectors is based on my current project
needs. Obviously, alternative combinations of signals can be achieved by using the
oscilloscope test points.

![Front](https://github.com/Fliptron/HP_Series_80_I-O_Extender/blob/master/Front.jpg "Front of Extender Card")
