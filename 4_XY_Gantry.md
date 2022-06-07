## XY Gantry Assembly

> :warning: **This page is WIP**

### Mounting XY Motors

> I'm using the LDO-42STH48-2004MAH "long bois" motors.  For the motors with couplers, the approach might be different.

Mounting the motors is pretty straightforward.  Mount the motor to the motor plate first, then mount them to the top of frame.

Fasteners: 16x `M3x10 SHCS`, 12x `M5x10 SHCS`, 8x `M5 roll-in t-nut`.


<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172307952-ec55af4c-6bf6-4bca-a7d8-6ad230c5b4c1.jpg width=300>
</p>

There's a couple things to be careful:

1. Make sure to push in the motor to the motor plate.  I believe the plastic holes are sized so that motors can be pushed in.  You can check if there's gap between motor and the plate:

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172308581-ab3d109c-f551-4dcf-9d26-da4576c68c66.jpg width=300>
</p>

2. The plates need to sit as flat as possible with the frame.  If there's some wiggle room, it's either the extrusions are not on the same plane, or the motor plate warped.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172324045-be4de574-ffb6-4618-9edd-098d4f700d98.png width=300>
</p>



### Gantry Rails

Fasteners(rails): 28x `M3x8 SHCS`, 28x `M3 roll-in tnut`, 16x `M5 roll-in tnut`

> I did NOT VC-3 these rail screws because I don't want any VC3 gunk to affect the rail.

Now flip the machine over, and install the gantry rails on the extrusions.  On all 4 sides, I first insert all the M3 tnuts, and also added 2 M5 tnuts on the outer side.  While we're on it, might as well insert the 2x M5 tnut on the inner side of the same extrusions.  These M5 nuts are for the Upper 625 Bearing holder and the Endstops.

There's a small problem here.  After installing the rails, I find that at each side, there will be not enough room for the m3 tnut to use the most outer holes on the rail.  I ended up mounting the rails without those 2 holes and give M5 tnut some space.  This can also be solved using some misumi spring tnut.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172326881-f52316b8-f463-47c3-9d00-27390e19be82.png width=300>
</p>


### Upper 625 Bearing holder + Endstops

Fasteners: 8x `M5x12 BHCS`, 4x `M5x14 SHCS`, 4x `M5x20 SHCS`

Now, with the machine still upside-down, we can install the upper 625 bearing holder and endstops.  Keep in mind that from this point on, we need to remember which side is the "front" of the machine.  I recommend make a mark for reference.

Installing the bearing holder is a little bit painful.  There's a few things:

1. Make sure the bearing can slide in to motor shafts.  Some longboi motors have tiny burrs that can potentially damage the bearing.
2. Make sure the bearing can fit inside the printed part.  Be careful not to damage the bearing.  It should be a good press fit.

The steps I end up taking is:
1. Pop the 625 bearing to the bearing holder part.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172330964-7474cdda-cb18-4c17-be4f-ab033c0ca9d5.png width=300>
</p>

2. loosen up or just unmount the motor plate, slide in the bearing/part into motor
<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172330511-f5550e4f-6900-44e1-88d9-886fc51cbf0d.jpg width=300>
</p>

3. Align the bearing part with extrusions first, then mount the motor plate.



### Cross rail mount

X rail mount blocks fasteners:  6x `M3x25 SHCS`, 2x `M3x20 SHCS`, 2x `M3x10 SHCS`

Y rail mount blocks fasteners:  6x `M3x45 SHCS`, 2x `M3x20 SHCS`, 2x `M3x30 SHCS`

Common: 4x `M3 square nuts`, 4x `6x3 magnets`, 4x `M3x16 SHCS`

...damn that's a lot of screws to VC-3.  For all the screws except M3x16, it's ok to just VC-3 the tip of it, since it's only the tip that will be screwed to the rail carriage.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/172331570-75e9eac2-57d8-4131-91d0-a5634d962b82.png width=300>
</p>

