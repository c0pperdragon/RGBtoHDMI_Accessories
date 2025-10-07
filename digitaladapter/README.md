# Digital adapter

This is a bridge from machines using a DB9 connector with
digital video output (MDA, CGA, EGA, C128) to the Analog RGBtoHDMI.

Up to 6 digital color signals are merged into 3 analog voltages. Seperate sync 
signals are also XOR-merged to create composite sync.

For its active circuitry to work, it needs to draw a small amount of power
from the +5V pin of the 6-pin IDC connector. As this is normally not supported
by the RGBtoHDMI, one small modification is necessary to the analog board.

