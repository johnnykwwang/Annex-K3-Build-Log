## Toolhead

> "Hold up, we are not done with Z assembly!" well, to streamline the build I think belting up Z can go with bed assembly, which is probably the next chapter.

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/182786365-c5f5cc3b-2e1b-4348-9c97-da3ae95be0ba.png width=300>
</p>

The toolhead is packed with details and there are a lot of variants.  For this build log, I'm building:

| Toolhead Item | Choice | 
| ------------- | ------------- | 
| Extruder | Sherpa Mini | 
| Hotend | Slice Mosquito Magnum | 
| Hotend Mounting | [Mosquito Net](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/main/Release_1_1/Experimental/K3_mosquito_net_RC1) | 
| Printed Parts Material | PC-CF |
| Wiring | Just Microfit-3 (No K3rabiner) |


### Sherpa Mini

Compare to other extruders I've built in the past, the Sherpa Mini is a simple yet elegant design.  To avoid confusion and provide the most up to date information, please follow the official [Sherpa Build Instruction](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/tree/master/Build_Instructions).

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/182902202-3e4eb853-5470-416b-ac2d-72f8570990b7.png width=300>
</p>

We can see that the front piece is different, there's an additional mounting hole.  This is to provide extra rigidity when mounting to the main  toolhead body (aka party plate). 

I recommend using the [Bondtech internal set for Sherpa Mini](https://www.bondtech.se/product/bmg-internals-set-for-sherpa-mini/).  This set does not require grinding the main shaft, and comes with all the screws necessary.  

Some additional notes:

1. VC-3 all the screws!
2. Make sure to clean up the filament path with a 2mm drill bit.

### Mosquito net

First, let's install the mosquito net.  I forgot to took picture when installing the mosquito net because I'm being very careful not to break the hotend :)  

Basically, disassemble the mosquito hotend and take the heatsink.  You can follow [Slice's disassembly instruction](https://support.sliceengineering.com/portal/en/kb/articles/mosquito-assembly-and-disassembly-instructions-r2-2).

Put the heatsink upside down and install the mosquito net with M2x4 flat screw.  Basically just like this image from the K3 github:

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/183238093-22e68332-962d-4504-bcdc-0f31b9ad387e.png width=300>
</p>

After that, carefully reassemble the hotend.

### QD2 and QD2 probe mount

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/183238283-4185fe99-04f8-4fc6-995f-a9df98d9afb6.png  width=300>
</p>

Assembling the probe for QD2 is a lot more streamlined than QD1.  I followed [Papejelly's instruction](https://discord.com/channels/641407187004030997/751424723669221566/965624204827431022):

- Place heatset insert on both "ear", and 1 on the side. 
- Strip two wires, thread through the magnet hole and make a loop.
- Press in the 6x6 magnet, make sure the wire are tucked nicely
- "Clamp" the magnets with a M3x8

<p align=center>
<img src=https://user-images.githubusercontent.com/13166286/183238424-fe110e14-5dea-4c13-8f24-97bbc3104516.png  width=300>
</p>

### Putting it all together

> WIP

