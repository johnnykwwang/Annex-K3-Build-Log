# XY Bearing & Belts

It's been a while...But I'm back :)

In the last part, I mounted all the necessary XY gantry parts and test drive the cross rails.  Here, we're finishing up the XY bearing stack and belt them up.


## Bearing Stack

Fasteners (bearing holder): 8x `M5x20 SHCS`  

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178526559-a52ae344-8bf3-4359-9a2a-c2d651a24441.png width=300>
</p>

First, install the "lower" bearing into the lower bearing holder.  For me it's a little bit hard to press fit the bearing in, so I use a buttom head M5 screw and a nut, and screw
the M5 screw until the bearing is locked in place.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178538332-5a2b8e10-77b2-40a4-9631-28261a222394.png width=300>
</p>

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178527341-9c32ec88-7bd9-4ad3-bb67-3eb2ae808d06.png width=300>
</p>

Then it's time for shims and idler stack.  For this, make sure to check the [K3's Github "XY Shim Placement"](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/main/STLs/XY_Gantry#xy-shim-placement) on how to add shims correctly.

For the Fabreeko's bearing and idler, since the idlers/pulleys are 13mm/19mm, it requires a bit different setup.  I ended up with something like [Ryan G's suggestion here](https://discord.com/channels/641407187004030997/852302000834084924/995834812524920922).

| Lower                   | Upper                   |
| ---                           | ---                           |
| ![image](https://user-images.githubusercontent.com/13166286/178528259-7f9b176a-89ba-461d-b0ee-fd0a0e9a4daf.png) | ![image](https://user-images.githubusercontent.com/13166286/178528280-7958696d-c5d2-4a60-8ac1-66a60816baf5.png) |

Before installing the whole stack of shims, idlers and pulleys, I did a final sanity check to make sure the stack aligns.  Take some rod and put upper and lower stack on, and see if the "belt path" aligns:

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178529184-48a25cae-d86b-412d-9487-a2ad728bb49a.png width=300>
</p>

Looks like it aligns pretty well!  Now it's just installing the stack to the long boi motor shaft, and mount the lower bearing holder to the frame.

**Remember, the machine is upside down, careful about the orientation of the stack!**

Also, remember to vibra-tite the set screw and lock the pulley in place on the XY motors!

## XY Belt

Fasteners (tensioners): 4x `M3x40 SHCS`  

> Disclaimer: I actually belt up XY belt way after Z assembly, but I think it's better to do it here.

Before belting up XY, double check if the pulley set screws are fastened.

Belting up XY is very easy compare to CoreXY belts.  I recommend looking at edrawing's belt path and making some components transparent.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178532891-a9fc9911-c153-4b57-8e6d-b0cd980b31b4.png width=500>
</p>

Each XY belt is around 600mm long.  I cut 4 600mm long belts and make sure the teeth counts are the same.  

First, take one end of the belt, and push into the tensioner where the belt meets a m3 screw.  Loop around the M3 screw, tuck in a few teeth, and pull hard to make sure it is secured.  It should look something like this:

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/178539090-e14a0298-3754-4baa-8d77-25027da85c1b.png width=300>
</p>

Then, just loop around the motor pulley and idler, place the other end on the belt tensioner (remember the heatset insert!) and screw the tensioner with m3x40.

If the belt is very loose when the M3x40 buttoms out, unscrew the tensioner and cut a few teeth off.  Remember to cut the same number of teeth on all other belts.
