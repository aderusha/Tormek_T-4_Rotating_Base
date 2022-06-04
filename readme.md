# Tormek T-4 Rotating Base

Tormek sells a rotating base for the sharpening system for $70, which I guess is reasonable if I had any money left over after buying all the damn accessories for this thing. Couldn't figure out how to print that drill sharpening jig (yet) but the base seemed doable, so i doabled it.  This repo has the results.

This model is a functional rotating base for the Tormek T-4 Sharpening System, similar in spirit to the [RB-180](https://amzn.to/3auJWnO).  The base rotates freely on a large ball bearing and has a locking tab to allow for easy positioning.

## Features

* Low-profile rotating base with lock/detent in various position. Three different models are provided depending on how many locking positions you prefer.
* Utilizes low cost "[slingshot ammo](https://amzn.to/3NVoNl4)" to create a large ball bearing capable of supporting the weight of the Tormek system
* Print area of 204mm x 200mm should be compatible with most i3-style FDM printers
* Source model provided and project is permissively licensed

## Bill of Materials

* Qty 24 [3/8" slingshot ammo](https://amzn.to/3NVoNl4)
* [CA "super" glue](https://amzn.to/3GO03Ja)
* [Light grease for bearing ways](https://amzn.to/3tgCW4C) (optional)
* [PLA filament](https://amzn.to/3xg61j2) for maximum rigidity

## Printing Notes

This project is going to be carrying a lot of weight and is tightly toleranced, so I'd recommend a [high quality PLA filament](https://amzn.to/3xg61j2) for maximum rigidity and dimensional accuracy.  Likewise, maybe crank up the perimeters and infill to make sure the resulting piece is rigid enough to handle the weight of the sharpening system.  All parts will print without support in the orientation provided.

Three models are provided for the bottom with [two](Bottom_-_2_side_detent.stl), [three](Bottom_-_3_side_detent.stl), or [four](Bottom_-_4_side_detent.stl) detent positions.  If you're just going betweent the front and back, select the [2 side detent](Bottom_-_2_side_detent.stl) model which will work like the OEM model.  I often find myself rotating my unit to the grinding wheel side so that I can set the angle via the [WM-200 Angle Master](https://amzn.to/3xs7LpD), so a [3 side detent](Bottom_-_3_side_detent.stl) model is provided which allows locking on one side.  I also threw in a [4 side](Bottom_-_4_side_detent.stl) model because why not.

## Assembly

1. Start with your [bottom piece](Bottom_-_3_side_detent.stl) and add a liberal dose of some light grease along the bearing raceway
2. Place [24 3/8" bearing balls](https://amzn.to/3NVoNl4) in the raceway
3. Place the [Bearing Spacer](Bearing_Spacer.stl) on top of the 24 bearing balls, one per hole in the spacer
4. Apply a thin bead of CA glue around the top edge of the [Top](Top.stl) and press-fit the [Top Bearing Raceway](Top_Bearing_Raceway.stl) into place.  [Take care to avoid getting glue on the inner surface](images/Top_glue_surfaces.png).
5. Apply a generous dose of grease along the bearing raceway of the Top, then place the assembled Top onto the assembled Bottom, aligning the bearings into the raceway. Give it a spin, it's fun!  Whoops not that hard, now put the balls back into the spacer and stop playing with the thing or you'll just have to do it again.
7. Apply a thin bead of CA glue around the bottom lip of the [Inner Retaining Ring](Inner_Retaining_Ring.stl), taking care to avoid getting glue on the bottom or inside of the part.  Then apply light grease around the outer edge.  [This diagram shows the detail](images/Inner_retaining_ring_glue_and_lube_surfaces.png): green areas get grease, blue areas get glue, red areas are avoided. Then press fit this part into the bottom.  It should be glued to the bottom while allowing the top to spin freely around its circumference.
8. Drop the [Locking Lever](Locking_Lever.stl) into the Top, it just rests there and is held into place by the T-4 sitting on top.
9. Place the T-4 onto your new base, making sure to align the larger rubber feet with the 4 corners of the Top, and making extra sure to align the smaller 4 plastic feet underneath with the cutouts provided on the Top.  Those 4 feet are offset from center, so if you put it on backwards those feet won't sit into their spot and it won't sit right.
10. Spin your sharpener right round like a record, baby!