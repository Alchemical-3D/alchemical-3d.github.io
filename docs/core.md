# Alchemical 3D

> Modular design, fully enclosed or open air CoreXYZ FDM 3D printer with direct drive and bowden extrusion system support, including the Alchemical-3D Pestle system for CoreXY.

 ![Alchemical Core Teaser](/assets/images/img_core/alchemical-3d_core.png)

## Project goals

- Fully Enclosed or Open Air design by builders choice.  Removable and printable panels afford the builder options to customize, add, or remove features based on need and cost.

- Support for multiple build volumes up to ~350mm and potentially larger later.   Initial printer release is focused on a 300x300x300 build volume.

- Support for wide range of filament types including all of the "typical" selections makers are used to working with, PLA, PETG, ABS, ASA, TPU, etc.

- Advanced sensor suite options including laser triangulation, filament width detection, accelerometers and more.

- Printing speeds up to 300mm/s

- Easy first layer calibration and auto detection of print issues using integrated lasers and camera system.


## Features


- Automatic Pressure Advance tuning using our laser triangulation system.

- Automatic Extrusion Multiplier tuning using our laser triangulation system and Pestle extrusion system.

- Built in resonance tuning and compensation with accelerometers usage integrated into klipper and the physical printer design.

- The 9mm belts minimize undesireable stretch and noise in the system resulting in superior printing quality.

- Belt driven Z-axis creates a higher resolution Z plain for the maker and enables faster Z-hop maneuvers.  Z-Hop can be critical to printed part quality in some cases.

- Easy to access to belt tension mechanisms ensure the system is at peak performance at all times.   All belt tension systems are mechanically assisted, no more wedging a screw driver in and pushing while trying to tighten with a free hand.  Grab a hex wrench and go.

- Optional, (but integrated) chamber air circulation and ventilation systems so the maker can print filament in classes such as ABS and ASA indoors.

- Optional, (but integrated) filament drying solution known as Retort, an advanced intelligent system with integration into Klipper for both drying and storage of filament.

- All motors outside heating chamber (except when using Direct Drive Config) reducing motor temperatures allowing higher current delivery.  Offering this slight overhead to the motors allows the user to increase current for more torque.

- External electronics bay keep those sensitive electronics from overheating during operation.  When electronics overheat they begin throttling.  This throttling can cause prints to fail or other defects during operation.  


## Key parts

- Retort like other Alchemical-3D projects is an open-source endeavor.

- The system can be built in the makers own workspace.

- Alchemical-3D toolhead system supports Goliath, Dragon and V6 hotends with more to come.

- NEMA 17 - 42STH48-2504AC - SPEEDY POWER or equivalent and better as standard for X/Y/Z-axis including support for larger variants.

- All main stepper motors are outside of heated chamber (below/rear) with X/Y-Axis motion receiving exhaust as active cooling.

-  24V Power Standard, 48V Optional.   Additional space provided under printer for makers who desire to add 48V power supplies.

- 2020 frame members and gantry frame with optional bracing.

- 1x MGN12H rail on X-axis, 5x MGN9H rails make up Y/Z-axis.

- 9mm 2GT belts on X/Y/Z-axis.

- Heavy Duty Bearings and bolts ensure your parts stay where you want them to.

- Printing out of ABS or ASA is required, PC or PC-ABS are also acceptable materials.

- Fysetc Spider, Octopus, Manta M8P MCUs are all supported.



-  Mains bed (with heating pad) or 24V bed by user choice, mains bed is recommended for this build due to volume and heating times.

## Software

-  Klipper + Mainsail or Fluidd

-  Pre-configured Alchemical-3D software and macros bundle.
