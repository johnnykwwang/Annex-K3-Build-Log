# Annex-K3-Build-Log
A personal build log of Annex K3 printer. 

## Preface
This is a personal build log of the [Annex K3](https://github.com/Annex-Engineering/Gasherbrum-K3) printer.  

At the time of this writing, [K3 is at RC1 stage](https://github.com/Annex-Engineering/Gasherbrum-K3/releases/tag/R1RC1).  It is very likely that some components or parts of the build already changed.  Therefore, this should not be considered as a build guide.

However, I will try to document every detail during the build.  This means from sourcing, printing parts, component preparation, building, wiring, and so on.  I will also point out any questions & doubts I have during the process.

## Table of Content

1. Background & Why K3?
2. Sourcing & Component Selection
3. Build Plan
4. Frame
5. (...to be continued)

## Background & Why K3?

### My opinions on the VORON V2.4

Before beginning the K3 build, I've built the VORON [V2.4](https://vorondesign.com/voron2.4) and [V0.1](https://vorondesign.com/voron0.1).  For the most part I really like my V2.4, it's been a great workhorse machine and I enjoyed printing parts with it.  However, there are some designs that I find it painful to work with.

> Note: These are my personal opinion.  There's probably a mod for a lot of things I've mentioned.  If we factor in mods, we'd also have to take care of compatibility between mods and updated revisions.  Therefore the discussion here is mainly on the stock printer design.

1. **Faster Printing**.  I enjoy prototyping and faster iteration always helps.  My VORON v2.4 can barely speed up to 250mm/s with 10K acceleration, without loosing quality.  This is very reasonable as V2.4 is not meant to be a speed printer.  Considering the toolhead & X gantry weight, the belt length, it is pretty hard to push the machine faster.  

2. **Getting rid of cable chains**.  Cable chain has been a PITA during the build and maintainence on my V2.4.  If given the chance I would build it with Umbilical wiring.
 
3. **Gantry Squareness & Belting**.  Deracking the V2.4 requires 4 Z on the same height & ideally QGL-ed to the build plate, AND perfectly belting two belts to the same tension.  Most of the CoreXY printer would have this problem.  This doesn't cause a lot of trouble once it's squared and deracked, but it is a painful process to build and it makes me less willing to take down & modify the gantry once it's built.

4. **Easier Electronics Access**.  All VORON printers put the electronics on the bottom of the machine.  It's very painful to flip the machine just to unplug & plug something.
 
4. **Official support for the Slice Mosquito hotend**.  This is a highly controversy topic.  But I personally really like the Mosquito hotend (shrug)

(...there's probably some more...)

### ANNEX enters the chat

Knowing ANNEX from the famous Sherpa extruder and QuickDraw probe, I begin to look at ANNEX printers.  I don't have a lot of printer space left and I don't need a monster build volume, so K3 is naturally my top choice.  After looking at the K3, on paper I found that it addresses most of the problem I have.  More importantly, it is designed with speed and ease of maintenance in mind.



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

### Structural


### Motion

### Electronics


### Wiring


### Fasteners

### Hotend & Extruder

### Bed

### Panels & Electonics Box


### Miscellaneous Parts



## Build Process

There is no official "build guide" for Annex K3.  I will be follow the e-drawing and the [build order provided by ActualVarner#5006](https://discord.com/channels/641407187004030997/852302000834084924/916480019998584843):

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

## Sourcing & Component Selection

## Component Preparation

##

