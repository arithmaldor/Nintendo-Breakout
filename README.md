# Copyright and Disclaimer
Copyright: Jacob Proctor

This documentation describes Open Hardware and is licensed under the
CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions

# Nintendo Multi-out Breakout
Breaks out all of the signals from the Nintendo Muliout so you can easily access them. 

# Operation
Plug in and go. There is a solder jumper to set the csync coming from the HD-15 port as TTL or 75ohm. Closed is TTL, open is 75 ohm. If you only plan to use this in TTL mode the resistor is not required.
This adapter can only break out signals that are already present. Unmodded SNES Jr. will only output composite, unmodded N64's will only ouput CVBS and S-video, same for Gamecube.
A cool extra feature is that this breakout lets you easily output component YPbPr from the GCDual and N64Advanced mods.

# PAL Systems
This was designed with NTSC systems in mind and is not compatible with PAL systems.

# Parts
Refer to BOM.csv for all components. For the support leg, use any appropriately long brass/metal m3 standoff/pillar and screw a rubber foot to the bottom. Solder a 5mm spring clamp to the bottom of the board to adjust the height.
For a Gamecube with Gameboy Player, standoffs may need to be screwed into each other (stacked) to reach the needed height.

# Case
The incredible [Magic Trashman](https://twitter.com/MagicTrashman) was kind enough to design 3D printable cases for both my Nintendo and PSX breakouts. They are under the same license as the PCB and are free to use, but if you order through thingiverse you can leave him a nice tip. Current designs fit the height of the original PS1 and the original SNES, but can be easily adjusted for height if you have some basic 3D design skills. They are held together with 2x 14mm M3 machine screws.
Pictures: https://t.co/ojJ8epfZXH?amp=1
Thingiverse: https://t.co/7dF171BqaF?amp=1
Bonus: If you plug the Nintendo/Sony connector into the console and screw the PCB into the bottom of the case, it makes it a lot easier to solder the connector to the board as it is held in place.
