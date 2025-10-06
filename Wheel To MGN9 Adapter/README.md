# Wheel To MGN9 Adapter

This is the mod I first started working on. I was looking for options not
to have to buy a sheet of aluminium then drill and cut the plates. I used
purchased open-build plates for the Z axis, but this doesn't work for the
X gantry.

I noticed that the V-wheels posiion the plate approximately 4mm above the
top of the extrusion, where as an MGN9 carriage positions it 10mm above
the extrusion. It is known that the aluminium plates cannot be 3D printed
because 3mm thickness is not rigid enough.

So I thought that if I 3D printed a 6mm plate that should increase rigitity
and bring the alignment in line with an MGN9 carriage. So I decided I
would design a 6mm adapter than would look like an MGN9 carriage for the
stock parts to mount onto.

I have done a few revisions of this in order to move the inner wheel out of
the way of potential toolheads. I also had to move the rear outer wheel back
to provide stability against twisting. I believe it works well as a stop-gap
until you can install rails. The only negative is that you cannot adjust the
wheel tension without removing the stock parts from the top. So make sure
you adjust the wheel tension before full assembly.

## Printing

Print with the flat side down, it should import in the correct orientation.
No supports are necessary.

## Installation

Install the heatset inserts before the wheels.

You will need 4 heatset inserts per adapter, M3x5x4, which go into the 4
inner holes. The circular end on the insert should fit into the hole, then
push it all the way in with a soldering iron. They can be installed from
either the top or bottom, but provide a stronger connection if they are
installed from underneath. You will need either M3x10 or M3x12 bolts to
attach the X axis parts to the adapter.

Note: In order to get the insert properly aligned, I push it almost in,
then flip the part over and press down hard on a flat heat resistance
surface. The remaining heat alows the insert to go all the way in, and
the flat surface ensures the insert is properly aligned.

Obtain 2 fixed position V-wheel assemblies, and 1 adjustable V-wheel assembly
from your box of Ender 3 parts (I used parts from the Z-axis).

The fixed wheels go on the outside, and the adjustable wheel on the inside.
Install a bolt, the bolt head should sit in the recess so that the top of
the adapter is flat. Put on either a spacer or the adjuster cam, then a
wheel and finally a bolt.

The fixed wheels can be tightened. Keep the adjustable wheel loose. Install
on the extrusion, adjust the cam until there is no slop, an you can still
turn the wheels with your fingers. The adapter should easilt slide back
and forth on the extrusion. Remove the adapter and do a final tighten.

They are now ready to install the stock X axis parts on top.

## CAD

The part is designed using FreeCAD. I can't provide STEP files, sorry, as
FreeCAD can only import STEP files, it cannot export them as far as I know.
