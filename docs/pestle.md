# Alchemical 3D - Pestle Extruder

> A flexible Bowden system designed to fit almost anywhere, while providing rotational movement to support even shorter bowden assemblies.
> https://github.com/Alchemical-3D/Pestle_Rotational_Bowden

 ![PestleExploded3.png](/assets/images/img_pestle/PestleExploded3.png)

## Project Information

- This is the Pestle Rotational Bowden, part of the Mortar and Pestle ecosystem.

The goal of this project is to provide an ultra lightweight but powerful extruder which rides the X gantry (or anywhere else you wish) while also being able to rotate allowing the shortest Bowden tube possible. This rotation removes the need for additional bend radii in filament path to toolhead.  On top of the PTFE length savings, the filament route results in lower PA value than a traditional Bowden, while preserving retraction settings which are more in line with Direct Drive. All of these benefits combined create a system that preserves the best from both worlds.

- Support for wide range of filament types including all of the "typical" selections makers are used to working with, PLA, PETG, ABS, ASA, TPU, etc.


## Features


- Lower PA ceilings than traditional Bowden solutions (better).

- Lower retraction values and requirements than traditional Bowden solutions (better).

- Reduced weight on the toolhead allowing higher acceleration/decelleration values in relative to system capabilities at any given time.

- Shorter PTFE length and fewer bend radii, resulting in a cleaner less resistive feed system.

- The medium sized buffer in filament path created by this system compensates for issue #6 (#602) allowing cleaner prints like a normal Bowden assembly.


## Key parts

- Pestle like other Alchemical-3D projects is an open-source endeavor.

- The system can be built in the makers own workspace.

- Pestle uses a round NEMA14 (or similar) 36STH20-1004AHG.

- Pestle is built with a typical Bondtech BMG parts kit. 

- Printing out of ABS or ASA is required, PC or PC-ABS are also acceptable materials.

- Pestle excels when used on a bedslinger, but can be used on CoreXY and similar, another version of Pestle is in development specifically for CoreXY and adds sensory functions to the extruder.



## Firmware Compatibility

-  Klipper

-  Marlin

## Notes:

- This assembly comes in relatively close conditions to a heated bed and stepper motor. We will not support issues due to using materials such as PLA to build this assembly. PLA and similar materials (PETG/PLA/PLA+/ETC) are NOT suitable to build 3D printer parts out of, please do not ask if PLA is ok, it is not. If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing current to your motor. Steppers produce heat and PETG (while better than PLA) still has a lower TG point, it could begin melting.

- The maker is responsible for your own safety and equipment when building and using this system, you accept all liability when using these files and printed items from both pre and current release candidates!

- The concept for this extruder was inspired by the now defunct Voron Jetpack. However, we would like to extend a special thanks to the Voron team for their inspiration on this product. Please take a moment if you are not familiar with the Voron project to educate yourself on the hard work they commit to the makerspace. https://vorondesign.com/
