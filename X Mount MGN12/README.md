# X Mount MGN12

This mod is for Duender MGN9, however it confusingly supports an MGN12 rail
on the X axis. Doing this expands the toolhead options as effectively any
Voron toolhead will simply fit as-is. I have a StealthBurner on mine, and
I used the Voron X Carriage STLs to mount it. However XOL, A4T, Archetype,
DragonBurner, etc will all simply bolt on. I would also like to experiment
with a StealthChanger for multiple heads in the future, and this mod
enables that. Some toolheads still support MGN9, but it is not as many as
supports MGN12.

Essentially all this mod does is move the idler pulley positions 3mm forward
to cater for the extra height in the MGN12 rail. I also fiddled with the
cutouts on the top to make it easy to get an allen wrench onto the bolt
underneath. This was a re-design in FreeCAD rather than an STL remix.

## Printing

Print with the flat side down, it should import in the correct orientation.
No supports are necessary. There are builtin bridges for the recessed holes,
so I suggest using a part cooling fan by the 3rd layer or so.

## Installation

After printing, install heat-set inserts in the left and right lower parts.

You will need 10 heat-set inserts in total, M3x5x4, installed as per the
original part. The circular end on the insert should fit into the hole, then
push it all the way in with a soldering iron. I recommend that they be
installed from bottom, as that provides a stronger connection. Note that for
the hole with the 10mm column, they can only go in from the bottom.

Note: In order to get the insert properly aligned, I push it almost in,
then flip the part over and press down hard on a flat heat resistance
surface. The remaining heat allows the insert to go all the way in, and
the flat surface ensures the insert is properly aligned and flush.

You will also need 10 x M3x30 bolts in total, along with bearings and shims.
All of the standard Duender MGN9 hardware fits in the equivalent locations.

Note: Shim stacks. In order to match the Voron belt spacing (4mm between the
inner edges of the belts) I have altered my bearing and shim stacks.
- On the stacks that have 2 bearing sets (the rear motor mounts) I use 1.5mm
of shims on the outside and 2mm of shims in the middle, and I don't use a shim
between the bearing halves because I don't want the belts moving up and down.
- On the stacks with a single bearing set, I use 1.5mm of shims on both sides.
Again no shims between the bearing halves.

## CAD

The part is designed using FreeCAD. I can't provide STEP files, sorry, as
FreeCAD can only import STEP files, it cannot export them as far as I know.
