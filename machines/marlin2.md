### Marlin 2.X

https://marlinfw.org/

Use this if you have a marlin version *higher* than 2.0.6

You must activate the folowing, default disabled, config option in Marlin:

`#define GCODE_MOTION_MODES // Remember the motion mode (G0 G1 G2 G3 G5 G38.X) and apply for X Y Z E F, etc.`

It is in the Advanced Config options, around [line 3197](https://github.com/MarlinFirmware/Marlin/blob/2.0.x/Marlin/Configuration_adv.h#L3197)

- [Configuration](https://marlinfw.org/docs/configuration/configuration.html)
- [GitHub](https://github.com/MarlinFirmware/Marlin)

First created in 2011 for RepRap and Ultimaker by Erik van der Zalm et. al., today Marlin drives most of the world's 3D printers. Reliable and precise, Marlin delivers outstanding print quality while keeping you in full control of the process.
