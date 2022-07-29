## Z Assembly

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181857802-0e47085b-84e6-489b-96eb-0992a3daf36a.png width=300>
</p>

Look at the size of just 1 Z drive part!
First, before we begin, check if the Z drive print is warped.  Mine is barely visible but I think there's still some very tiny warping.  Check [Ellis Guide on Bed Adhesion](https://github.com/AndrewEllis93/Print-Tuning-Guide/blob/main/articles/build_surface_adhesion.md) to help print this part.  Or just stick some VM goo.

### Prep Work
1. Check the edrawings and make sure to insert all the heatsets.   There's some M3x35 SHCS screws on the motor mount that's purely for strengthing the part, as you can see in the left side:

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181860261-4217607f-1349-4c75-960c-e00ff38708ae.png width=300>
</p>

2. Test fit if the shaft, bearing and idlers fit together nicely.
3. Test fit if the 625 bearing fits inside the Z assembly part.

### 80T/20T stack

First, let's deal with the most annoying part of the assembly:  the stack with 80T/20T gear.  [Przy provided a pretty good instruction](https://discord.com/channels/641407187004030997/852302000834084924/926752999970320495) on how to assemble the stack, and I'm following the exact same steps for all 3 drives.

<table>
  <tr>
     <td> 1. Seat the 625s in the end spots on the z drives (not the middle) </td>
     <td> <img width="500" src="https://user-images.githubusercontent.com/13166286/181859453-600fd3ce-530f-4be7-9d20-7997f09b5655.jpg"> </td>
  </tr> 
  <tr>
     <td> 2. Put a shaft in from the outside toward the 80t spot </td>
     <td> <img width="500" src="https://user-images.githubusercontent.com/13166286/181859477-e099d382-94f5-4c07-bea1-f312a898a277.png"> </td>
  </tr> 
  <tr>
     <td> 3. Washer on shaft, and put on 80t WITH THE CLOSED TOOTH BELT ON ALREADY, and another washer.</td>
     <td> <img width="500" src="https://user-images.githubusercontent.com/13166286/181859560-b4ac1733-a9b4-4a8e-838d-89b9029e918a.png"> </td>
  </tr> 
  <tr>
     <td> 4. Put in middle 625 bearing and thread the shaft through.  Then the washer, 20T and last washer in.  It's pretty hard to put the last washer in, I snug the washer in and use a thin tweezer to push it in, and thread the shaft through.</td>
     <td> <img width="500" src="https://user-images.githubusercontent.com/13166286/181859751-1aecc406-f91b-4098-9af9-3d18ccda1087.jpg"> </td>
  </tr> 
  
  <tr>
     <td> 5. Push shaft rest of the way up and through the bearing, center the shaft as best you can, and tighten grubs. </td>
     <td> </td>
  </tr> 
  
</table>

Please double check if you put in th eclosed tooth belt.  If not you'll have to redo nearly the whole stack.  Repeat the process for all 3.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181860099-bda7d650-dc5a-445e-b440-0d7afe1053be.png width=300>
</p>

### Mounting Z motor 

> Screws: 3x `M3x8 SHCS`, 3x `M3x30 SHCS`, 6x `M3x35 SHCS`

1. Put the motor gear on motor shaft, place the motor on the motor mounting hole.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181860747-8360eadc-8a40-4ab5-a6d1-a231c135d9c0.png width=300>
</p>

2. Loop the closed belt into the motor gear.  Position the gear such that it aligns with the belt path, and tighten the grubs.

3. Loosely put on 4 screws for the motor.  There's one screw that's shorter (M3x8) because it's in the belt path. 

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181860829-af43404b-c563-443f-9ef6-49645d79cfa3.png width=300>
</p>

4. Pull as hard as you can on the motor to give the close belt enough tension, and tighten the screws.  I [had a discussion](https://discord.com/channels/641407187004030997/852302000834084924/985615506553856100) about how to do this and there's some video showing how tight it should be.

### Idler stacks

Finally, there's the smooth and tooth idler for the long Z belt.  These are very straightforward and I forgot to take pictures, but basically just two washers, idler and the shaft.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181861041-97783f7c-b53f-4dff-9153-880113613f55.png width=300>
</p>

### Mounting to the frame

> Screws: 12x `M5x16 SHCS`, 4x `M3x10 SHCS

Mounting to the frame is also pretty simple.  I put the machine 90deg with the bottom facing us, and install the Z drive parts.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181861258-e4920317-2875-4b4b-8af9-72ba4b8e6d84.png width=300>
</p>

There's also this part that provides a bit more ridigity.  But it's pretty painful to screw on unless you have a low-profile allen key.  Another approach is to assemble these two front Z drives with the "bridge" part first, and install them all as one part.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/181861315-f362c7a5-edf4-4ebd-bafa-1088da9a72a0.png width=300>
</p>
