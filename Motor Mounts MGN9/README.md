# Motor Mounts MGN9

This project contains a re-design of the motor mounts from Andizzle, however
adds 8mm to the deck height to make them compatible with the MGN9 project.

I also removed the trianguler mount from the bottom, as in the future I will
have a 20x40 extrusion there to support a 3rd heated bed mount. It seems
plenty strong enough without it.

Finally it uses the M5x45 bolts from the Ender 3 (you need to tap your
threads into the extrusion at least 20mm) to mount into the 2040 Y-axis
extrusions to make for a very strong connection.

You need to mount both of the motor mounts to 2020 extrusion first, as the
M5x45 bolts prevent access to the bolts that go into the end of the 2020
extrusion. Then you use the M5x45 bolts to mount the assembly to the frame.

Note that this redesign moves the bolt positions somewhat, so that you cannot
mix and match the top and bottom parts from Andizzles project. The belt path
remains compatible so there should not be any effect on kinematics.

## Printing

Print with the flat side down, it should import in the correct orientation.
In order for the flange bearing recess to print correctlty, enable manual
supports, and paint the circular flange bearing recess in the slicer, and
when sliced check that support is generated just in that area.

I hope to produce a file with support designed in, but for now you will have
to use manual support and paint it on. Automatic support will work, however
it will fill the holes intended for the heatset inserts, and they are a
pain to remove.

## Installation

You will need an M8 tap to cut a thread into the largest hole. This should
be easy as it is just plastic. I will try and figure out how to design a
thread so it gets 3D printed in a future revision.

Next you need 5 heatset inserts per mount, M3x5x4, which go into the 5
middle sized holes. The circular end on the insert should fit into the
hole, then push it all the way in with a soldering iron.

Note: In order to get the insert properly aligned, I push it almost in,
then flip the part over and press down hard on a flat heat resistance
surface. The remaining heat alows the insert to go all the way in, and
the flat surface ensures the insert is properly aligned.

Move your bearing stacks from the existing top cover to the new top cover.

Mount the top cover to the bottom part. The existing bolts should be OK,
6 x M3x30 and 1 x M8x35 (from Ender 3 Y-axis tensioner).

You will likely need to tap a longer M5 thread into the end of your Y
extrusions. I have designed for the M5x45 bolts to have 18mm of thread
protruding from the mount, so I suggest extending the thread length to
20mm with a tap.

Use some tape on the tap to make the 20mm position. Make sure to use the
original thread to guide the tap in, as you don't want it cutting a new
thread that is out of alignment.

You will also need to tap a thread into the 2020 extrusion, the length
of the thread depends on the bolt length you use, but use a button head
bolt as there is no clearance for anything else. I would suggest an
M5x16 as a minimum to provide a strong connection.

You then mount both of the motor mounts to 2020 extrusion first. Start
with a T-nut and M5x8 from the back of the mount, don't fully tighten.
Next install the M5x16 into the end of the 2020 extrusion, tighten this
first then go back and tighten the M5x8. Repeat for the other motor
mount on the other side of the extrusion.

Finally use the M5x45 bolts to mount the rear-motor mount assembly onto
the frame. You might find that you need to flex the frame to line up
the bolts so that they go in.

The rear of the frame should now be very rigid, and you should look at
adding a brace to the front of the frame to provide similar rigitity.

## CAD

The part is designed using FreeCAD. I can't provide STEP files, sorry, as
FreeCAD can only import STEP files, it cannot export them as far as I know.
