# Motor Mounts MGN9 Extended

This project takes my previous MGN9 Motor Mounts project and moves everything
further back to allow more Y axis travel. You will probably want to have 320mm
rails (get 350mm rails and trim 30mm from it with an Inox cutting wheel on an
angle grinder) with these mounts to give 280mm of Y travel (45mm outside the
print bed area).

Also the top half is relocated a further 10mm back, as I was having a problem
with the toolhead PCB (one that mounts to the extruder stepper) hitting the
top mounted stepper motors. The top half of the mounts are the same as my
previous mounts, so no need to reprint if you already have them.

Also note that you will need longer belts as a consequence of moving
everything back. Belt alignment stays the same, just the run from front to
back is longer.

You need to mount both of the motor mounts to 2020 extrusion first, as the
M5x45 (or M5x40) bolts prevent access to the bolts that go into the end of
the 2020 extrusion. Then you use the M5x45/40 bolts (4 instead of 2 in this
version) to mount the assembly to the frame.

## Printing

Print with the flat side down, it should import in the correct orientation.
The parts are designed such that no supports are required to print. I suggest
4 walls, 5 top and bottom layers, and 40% infill for strength as this part is
under tension from the belts. This is the standard Voron printing specs.

## Installation

You will need an M8 tap to cut a thread into the largest hole. This should
be easy as it is just plastic. I will try and figure out how to design a
thread so it gets 3D printed in a future revision.

Next you need 5 heat-set inserts per mount, M3x5x4, which go into the 5
middle sized holes. The circular end of the insert should fit into the
hole, then push it all the way in with a soldering iron.

Note: In order to get the insert properly aligned, I push it almost in,
then flip the part over and press down hard on a flat heat resistance
surface (I use a small sheet of aluminum on my desk). The remaining heat
allows the insert to go all the way in, and the flat surface ensures the
insert is properly aligned when the plastic sets hard.

Move your bearing stacks from the existing top cover to the new top cover.

Mount the top cover to the bottom part. The existing bolts should be OK,
6 x M3x30 and 1 x M8x35 (from Ender 3 Y-axis tensioner).

You will likely need to tap a longer M5 threads into the end of your Y
extrusions. I have designed for the M5x45 bolts to have 19mm of thread
protruding from the mount, so I suggest extending the thread length to
20mm with a tap. Or use the M5x40 bolts with a 15mm tapped hole. Make
sure to use the original thread to guide the tap in, as you don't want
it cutting a new thread that is out of alignment. Make sure to tap both
the top and bottom holes.

You will also need to tap a thread into the 2020 extrusion, the length
of the thread depends on the bolt length you use, but use a button head
bolt as there is no clearance for anything else. I would suggest an
M5x12 as a minimum, and an M5x16 is even better.

You then mount both of the motor mounts to 2020 extrusion first. Start
with a T-nut and M5x8 from the back of the mount, don't fully tighten.
Next install the M5x12/16 into the end of the 2020 extrusion, tighten
this first then go back and tighten the M5x8. Repeat for the motor
mount on the other side of the extrusion.

Finally use the M5x45/40 bolts to mount the rear-motor mount assembly
onto the frame. You might find that you need to flex the frame, if it
is slightly out of alignment, so that the bolts go in.

The rear of the frame should now be very rigid, and you should look at
adding a brace to the front of the frame to provide similar rigidity.

## CAD

The part is designed using FreeCAD.
