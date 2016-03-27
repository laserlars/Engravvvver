# Engravvvver
Engravvvver GCode Generator

The Engravvvver is a vvvv patch that reads a pixel image (.BMP / .JPG / .PNG / etc)
an converts it into a machine-readable GCode path for 2D raster engraving.

Credits go to Jens A.E. for his help with raw data spreads, which made the engravvvver work
a lot faster and also enabled it to deal with >4k resolution. 

You can
- set the laser power (min/max) from 0-255
- set the travel and feed rate
- set the scan resolution (pixel size in mm),
- define a cutout shape (quad/circle) as well as cutout speed and power

You can not 
- send the gcode "on-the-fly" to an grbl/arduino device (Use Universal GCode Sender 2.0 nightly by Will Winder)
- achieve a higher feed rate than the _max amount of gcode lines per second_ that UGS will send

PS:
I must admit i'm n00b to git and version controlling and i don't like it very much.
Maybe it's too simple or too powerful, anyway: I just don't get it. Maybe someday i will get used to it. 
For now, please don't expect me to correctly push new versions all the time.
