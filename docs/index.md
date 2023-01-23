# Alchemical 3D

> Modular design, fully enclosed or open air CoreXYZ FDM 3D printer with direct drive and bowden extrusion system support, including the Alchemical-3D Pestle system for CoreXY.

 ![Alchemical Fire 1 Teaser](/assets/images/alchemical_fire1_web.png)

## Project goals

- Fully Enclosed or Open Air design by builders choice.  Removable and printable panels afford the builder options to customize, add, or remove features based on need and cost.

- Support for multiple build volumes up to ~350mm and potentially larger later.   Initial printer release is focused on a 300x300x300 build volume.

- Support for wide range of filament types including all of the "typical" selections makers are used to working with, PLA, PETG, ABS, ASA, TPU, etc.

- Advanced sensor suite options including laser triangulation, filament width detection, accelerometers and more.

- Printing speeds up to 300mm/s

- Easy first layer calibration and auto detection of print issues using integrated lasers and camera system.


## Features


- Automatic Pressure Advance tuning using our laser triangulation system

- Automatic Extrusion Multiplier tuning using our laser triangulation system and Pestle extrusion system.

- Built in resonance tuning with accelerometers usage integrated into klipper.

- Utilize 9mm belts to minimize stretch and reducing belt path lengths for reduction of noise and deformation in the system resulting in superior printing quality.

- Belt driven Z-axis creates a higher resolution Z plain for the maker and enables faster Z-hop maneuvers.  Z-Hop is critical to printed part quality by reducing stringing and blobbing on your parts.

- Easy to access and adjust belt tensions ensuring you can keep the system at peak performance at all times.   All belt tension systems are mechanically assisted, no more wedging a screw driver in and pushing while trying to tighten with a free hand.  Simply grab your hex wrench and go.

- Optional but integrated chamber air circulation and ventilation systems so the maker can print filaments such as ABS and ASA or others in a safer manor indoors.

- All motors outside heating chamber (except when using Direct Drive Config) reducing motor temperatures allowing higher current delivery.  Offering this slight overhead to the motors allows the user to increase current to these units for more torque.

- External electronics bay keeps those sensitive electronics from overheating during operation.  When electronics overheat they begin throttling.  This throttling can cause prints to fail or other defects during operation.


## Key parts

- 2020 frame members and gantry frame

- 1x MGN12H Rails for X stability for the hotend.

- 4x MGN9H Rails make up the Y/Z-axis, all redundant to ensure movement accuracy.

- 9mm 2GT Belts on XYZ axis Motion

- Heavy Duty Bearings and bolts ensure your parts stay where you want them to.

- NEMA17 Motors XYZ 4042 as standard, support for NEMA17 4048 for XYZ

- Printing out of ABS or ASA is required, PC or PC-ABS are also acceptable materials.

- Fysetc Spider, Octopus, Manta M8P MCUs are all supported.

- Alchemical-3D toolhead system initially supports Dragon and V6 hotends and many other to come

-  24V Power Standard, 48V Optional.   Additional space provided under printer for makers who desire to add 48V power supplies.

-  Mains bed (with heating pad) or 24V bed by user choice, mains bed is recommended for this build due to volume and heating times.

## Software

-  Klipper + Mainsail or Fluidd

-  Pre-configured Alchemical-3D software and macros bundle.
