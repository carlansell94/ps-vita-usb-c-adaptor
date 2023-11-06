A USB type C board for use with a Vita PCH-1000 (original model) charging connector. A charging connector assembly is required, as this board is designed to fit into the connector housing (trimming required).

Features:
* Includes pads for 5.1k&#937; resistors, to allow the use of 'smart' chargers.
* Compact design limits the board overhang using the original housing.

Included in this repository are the KiCAD files for this design. If you're only interested in having the board manufactured, gerbers are available under 'releases'.

Parts List:
* 1x 16 pin USB type C port
* 2x 0603 5.1k&#937; resistors (optional)
* 1x Vita PCH-1000 charging connector

When having the board manufactured, ensure they offer a 0.8mm board thickness - I used OSH Park for mine.

For more information, take a look at [my blog post](https://qubitsandbytes.co.uk/making-a-ps-vita-usb-c-charger).

## Image
KiCAD render:

![KiCAD render](render.png?raw=true "KiCAD render of the board")

## KiCAD
The USB Type C port pictured in the 3D render can be found [over here](https://github.com/ai03-2725/Type-C.pretty) - the file you're looking for is 'HRO TYPE-C-31-M-12.step'. It's not required, unless you want to see the part populated using the 3D viewer.
