# Here you can get all your rod lengths for i3 right.
If you are using single plate model, use *numbers*
"Default box" is made of 6 450mm boards and one that is 2 * board thickness longer, see http://78.47.92.212/i3_documentation_pics/06-frame.md.html

## Y axis
You need 2 smooth rods, 2 M10 rods and 4 M8 rods

### Y smooth rod length is sum of:
 * workarea (200mm)
 * belt assembly parts (100mm) or outer dimensions of Y bearings (100mm for Prusa3ALU-FREZOVANY-v4.dxf)
 * 40mm inside Y axis corners

for 340mm minimum. EiNSTeiN uses *400mm* rods, so I may be missing something here.
Take care they are cut exactly to the same length

### Y threaded rods (M8):
Sum of:
 * rod separation (170mm)
 * Y axis corner (20mm)
 * nuts and washers (15mm)

For *205mm*, or 210mm if you use nyloc nuts.
If your rods are cut right to the size (and are all exactly the same length) you will have easier time getting the frame right.

### Y threaded rods (M10):
Y Smooth rod + 30mm, so *430mm*. May be longer.


## X axis
You need 2 smooth rods

### X axis smooth rod is sum of:
 * workarea (200mm)
 * x carriage width (85mm for box carriage, 58mm for single plate)
 * 90 mm inside X end parts
 * for dualhead extruders, distance between hotends (70 for two extruders on box carriage)
For 376mm minimum with box model carriage. Its also box width minus 3 cm, so at least *370* for single plate, 450 for default box. May be longer.

## Z axis
You need 2 smooth rods and 2 M5 threaded rods

### Z axis smooth rod:
Box height - 50mm, so *320mm* for single plate, or 400 for default box. May be longer
### Z axis threaded rod
Smooth rod - 20mm, so *300mm* (or 380 for default box). May be longer.
