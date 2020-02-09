# DIN43880 enclosure and other DIN stuff

This was forked from e3DHW-make-DIY-electronics-hardware-like-a-professional and re-arranged (a lot)
to make it work better with git and to focus it on the generation of DIN43880 enclosures

still work in progress and teh TODO list is longish..

But my first contribution is to allow teh generation of slices through teh enclosure in order to be able to create fitting PCBs

Enjoy!

Bret

The evolution of the electronics from the single components to the macro-sets (boards and shields)
was positive, allowing the rapid prototyping of complex projects until a few years ago
unimaginable, thus bringing new audiences of enthusiasts to electronics.

I want to present some ideas to move from an electronic 'prototype' to a more stable and usable
realization, in a simple, quick and economical way.
With the use of a 3D printer and a series of OpenSCAD (https://www.openscad.org/) parametric libraries ready to use.

The use of the 3D printer allows to obtain tailor-made structures without the need of mechanical
workshop machines for cutting, bending or drilling. Also many accessories (ADDONs) such as
terminals, connectors etc. can be inserted into the 3D project by simplifying assembly and wiring.

![Watering Sonoff](images/sonoff400.jpg  "Sonoff watering timer") 

- For the full story, read the e3DHW_HOWTO_en.pdf file (versione italiana e3DHW_HOWTO_it.pdf)
- OpenScad libraries, last stable version, in dir OpenScadLibraries :)
- File help for all libraries: e3DHWref.1.2.chm.
- Also here: https://www.thingiverse.com/thing:2860353

#### Working version: 1.3
 - Added Power Management System (see 'power PMS/e3dhw-pms-intro_en.pdf')
 - Added 'power PMS/e3DHW_addon_batteries.1.3.scad'
 - Added 'base/e3DHW_array_utils.1.3.scad'
 - File help for working version: e3DHWref.1.3.chm.
