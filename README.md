# Modified files for Duender MGN9 Version

I wanted to use the updated MGN9 files for constructing my Duender. This
was because a number of improvements had been made to the design. Also I
I would like to install rails in the future without needing to reprint all
of the parts. The MGN9 has improved stacking of the flanged bearing using
0.5mm washers instead of printer shims.

I also saw the "Top Motor Mount w/ Double Shear for Duender" from Andizzle
on Printables, and liked how rigidly it mounted to the frame. However this
mount was not suitable for the MGN9 version.

These files are not re-mixes of the original STEP or STL files. I have
designed each one from scratch in FreeCAD using just the dimensions of
the original parts to make them work in place of the originals. However
I deem them a remix as they are intended for the Duender, and replace
the original parts in a like-for-like way.

I want to thank Sergei Irbis for the design of the Duender and providing
a means for my Ender 3 to continue as a useful 3D printer.

I also want to thank Andizzle for the improved motor mounts that I have
based my motor mounts design on.

## Front Tensions MGN9

This project contains a re-design of the front tensioner housings from
Sergei Irbis, and they re-use the stock pulley holder inserts.

The main change is that it uses the M5x45 and M5x25 bolts from the Ender
3 (you need to tap your threads into the extrusion at least 20mm) to make
for a very strong connection.

I have also adjusted the geometry to provide a solid end-stop for my newly
designed Wheel to MGN9 Adapters.

Finally I played with the asthetic to get something that I like better.

## Motor Mounts MGN9

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

## Wheel To MGN9 Adapter

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
