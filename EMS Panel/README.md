# EMS Panel

This is an EMS panel for the Duender 3D printer. What is EMS? It is a system
for managing the electronics for 3D printers from FizzyTechs. It consists of
a panel with hexagon cutouts, a set of hexagon shaped plugs that fit into the
panel, and a repository of mounts for various 3D printer electrical components.
The idea is that if you replace a component, or need to move one around, you
can just print the mount for the new component, or move the plugs to a
different cutout. There are also plugs for zip-ties, and a set of cable ducts
for solving any cable management issue.

https://www.printables.com/model/558357-ft-ems-mounts-repository

Note that there is no upper lid for the electronics bay, I was thinking a sheet
of Acrylic with a cutout or two for fans. The hexagon holes in the EMS panel
will allow cooling air to pass out from underneath the Duender.

## Printing

Print with the flat side down, it should import in the correct orientation.
No supports are necessary. There are some bridges, but they should print OK
provided you have some part cooling enabled.

The model is 288x249 so you will need a printer capable of 300mm. You can
use the slicer to split it into 4 parts, then super glue it back together.
There are “dog-bone” joiners available for EMS if gluing is not strong enough.

The dimensions should give you 1mm gap in both directions, however filament
shrinkage could cause more gap. So it's best to calibrate the shrinkage for
your filament and set that in the slicer before printing.

## Installation

The panel mounts in the bottom of the rectangle formed by the 4040 extrusions
in the base of the Duender. Your electronics mounts to the base using the plugs
and adapter mounts from the FT EMS repository. I suggest working out the
electronics component placement while the EMS base is not installed, as it will
be easier to make adjustments. Once you have worked out the positions, remove
the components from the mounts, install the panel and re-install the components.

Use 8 sets of M5x8 bolt and M8 T-nut (should have a bunch available from the
corner braket packs) to bolt it to the upper V-slot. The EMS base should be
flush with the bottom of the 4040 extrusions, and should clear the Z-axis
steppers if you didn't use spacers to place them lower.

## CAD

The part is designed using FreeCAD. I can't provide STEP files, sorry, as
FreeCAD can only import STEP files, it cannot export them as far as I know.
