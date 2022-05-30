# Annex-K3-Build-Log
A personal build log of the Annex K3 printer. 

## Preface & Disclaimer
This is a personal build log of the [Annex K3](https://github.com/Annex-Engineering/Gasherbrum-K3) printer.  At the time of this writing, [K3 is at RC1 stage](https://github.com/Annex-Engineering/Gasherbrum-K3/releases/tag/R1RC1).  It is very likely that some components or parts of the build already changed.  

**This should not be considered as a build guide.  Please refer to the e-drawing and the K3 repo for more up-to-date info.**

I will try to document every detail during the build.  From sourcing, printing parts, component preparation, building, wiring, and so on.  I will also point out any modifications I made to the printer.  As all DIY printesr, this machine would likely not going to be a "stock" machine.

If there's any feedback, feel free to find me at the Annex Discord, or ping jkwang#7099.

## Why K3

Why not?

Knowing Annex from the Sherpa extruder and the QuickDraw probe, I began to look at ANNEX printers.  After looking at the K3, on paper I found that it addresses most of the problem I have with the VORON V2.4.   More importantly, I like the Annex design philisophy: Printer with amazing performance and ease of maintenance.


## Table of Content

  * [Sourcing & Component Selection](1_Sourcing.md)
  * [Build Process - Planning](2_Planning.md)
  * [Frame Assembly](3_Frame.md)
  * ( To be continued! )


## Sourcing & Component Selection

> Note:  By the time you read this, the K3 BOM is likely updated.  Please refer to the latest BOM!

This is a log of what component I chose in the build and why.  

### Kits

I got a lot of parts kit from [Fabreeko](https://www.fabreeko.com/).  This helps a lot with sourcing the K3 as I don't have to hunt down each bearings, pulley and idlers.

| Component / Item | What I got | Notes |
| ------------- | ------------- | ------------- |
| Frame  | LDO K3 Frame |  |
| Motors  | LDO K3 Motors |  |
| Linear Rails  | HoneyBadger K3 Rails |  |
| Bearings Kit  | HoneyBadger Chrome Steel Bearings |  |
| Motion Kit  | Fabreeko's K3 Motion Kit |  |

Below are parts that are not covered by the kits.

### Printed Parts

I used 3DXTECH ASA Black and Grey to print the parts. 

> TBD:  Put image here

### Structural

I went with all the recommended bracket from Misumi, including the internal L bracket.  

| Component / Item | What I got | Notes |
| ------------- | ------------- | ------------- |
| Internal L Bracket - 2020 Extrusion  | HBLPBS5 |  |
| Misumi Perpendicular Bracket HBKUS5  | HBKUSB5 | Black version of HBKUS5 |
| Misumi Perpendicular Bracket HBKTST5  | HBKTSB5 | Black version of HBKTST5 |

### Electronics
> TBD

### Wiring
> TBD

Following some popular build on Discord, I decided to order MCPC-X cable sleeve as well.

### Fasteners

Too much to list.  Basically counting what I have on hand, and ordered the rest on Bolt Depot and McMaster-Carr.

### Hotend & Extruder

| Component / Item | What I got | Notes |
| ------------- | ------------- | ------------- |
| Hotend  | Slice Mosquito Magnum | What I have on hand, Supported by the [Mosquito Net](https://github.com/Annex-Engineering/Misc_Designs/tree/master/Mosquito_Net) |
| Nozzle | BondTech CHT 0.4/0.6mm | For that extra speed |
| Hotend Sock | TriangleLabs Socks | |
| Thermistor | Slice PT1000 | |
| Heater Cartridge | TriangleLabs 50W Heater | |

### Bed

| Component / Item | What I got | Notes |
| ------------- | ------------- | ------------- |
| Build Plate  | 1/2" MIC6 from Midwest | Kirby(ANNEX discord member) groupbuy. |
| Magnetic Sheet | McMaster-Carr Magnetic Sheet | |
| Heater Mat | Fabreeko Edge-to-Edge heater 300W | |

### Panels & Electonics Box

I got the aluminium panels from Nirecue's groupbuy leftovers.  Later in the build I will document how I paint and wrap the bare aluminium panels.

## Build Process - Planning

There is no official "build guide" for Annex K3.  I will be follow the e-drawing and the [build order provided by ActualVarner#5006](https://discord.com/channels/641407187004030997/852302000834084924/916480019998584843).  This section will be slowly removed as the build goes on.

> 1. Main frame, starting with the lower cross members (all 8 internal brackets).  Used both blind joints and internal brackets.  Do it on quartz/granite countertop if available. Exclude crossbars and bracing for Z until step 9.
> 1b. Bed frame assembly constructed in parallel as separate part.
> 
> 2. X/Y mounts and motors.  Installed as sort of part of the frame, wanted to do it early to ensure and enforce squareness.  This worked well with longbois, probably not as great an idea for couplers.
> 3. Gantry plastic parts to hold the top 625 bearings as well as plastic endstops.
> 4. Turn upside-down (motors down) and install gantry rails, gantry rail carriage attachments, and cross rails.
> 5. Test fit main toolhead part to the cross rails.  Re-print spacers if too big a gap, or lightly file the toolhead part until it's perfect.
> 5b. Ensure the cross rails are perpendicular to each other; @Ryan G recommends:
> - loosen 1 of the 2 rail carts on the toolhead plate
> - move both axes against the endstops
> - tighten the rail cart that you loosened earlier.
> - Ensure fluid motion.
> 6. 625 bearings, spacers, pulleys, idlers for X/Y motors (frame still upside down)
> 7. Cap the stack off with the "bottom" 625 bearing and add the plastic parts to retain the stack.
> 8. Belt up the X/Y gantry.  Check for cogging, binding, etc.
> 9. Turn right-side up. Add crossbars and bracing for Z extrusions to the frame.  Assemble Z motion system of choice. 
> 10. Entirely separately, and really at any point, you can start constructing the backpack on the rear panel.  No need to install this until after mechanical is done (and especially it would make the X/Y gantry much harder to do upside-down).
> 10b. Superglue spacers on to side panels and rear panel.  Attach the top hat plastic parts to the electronics panel with screws early, as the electronics box corners cover those screw heads.
> 11. Install electronics back panel which is done except for umbilical connections. 


## Frame Assembly
### Prep Work
1. To assemble the frame, I managed to find a 16"x16" quartz countertop piece at a local shop.
2. I choose to use M5x12 instead of the M5x8(BOM) on blind joints.
3. Counting the screw number, and pre-apply VC3 [1] on all the screws. Following the wisdom from the Annex discord, I will apply VC3 to all the screws in the printer. 

> [1]: Vibra-tite VC3 requires pre-applying and waiting for it to dry.  [See product page](https://www.vibra-tite.com/threadlockers/removable-reusable-threadlockers/vibra-tite-vc-3-threadmate/) 

### Tips & Tricks

> Check out [Nero3D's Video on how to build a squared frame](https://www.youtube.com/watch?v=GSg7RDLgYV0)
