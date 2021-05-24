# LineFollower_C

This repository contents the instructions to create a line follower with three sensors

This is another version from the last line follower (https://github.com/Diegollmll/Line_Follower_Assembly)

In the realization of this project, the PIC16F15244 Curiosity Nano was chosen as the controller, due to its easy way to get and to use it, in the same way the TB6612FNG driver was used, due to that it performs an incredible job controlling DC motors and stepper motors. This line follower robot has a 3 sensor strip that generates an output for the inputs of the TB6612FNG driver. To carry out the programming code, the MPLABX software was used, making use of the C language, to later simulate in the Proteus Professional software to make the pcb wiev and 3d view. The line follower robot moves along a 20mm wide line and stops at a 20cm wide black box.

This repository contents:

-Source code (C language)
-Schematic in Proteus Professional (File .pdsprj)
-PCB view in Proteus Professional
-3D view in Proteus Professional

Software requeriments:

-MPLABX (Version 5.40)
-Proteus Professional (Version 8.5)

Hardware requeriments (physical implementation):

-PIC16F15244 or similar
-Driver TB6612FNG or similar
-Gearmotors
-Sensors strip
-Programmer Pickit (Optional)

How to install:

-Download the project
-Load the source code in MPLABX
-Program the Controller

Authors:

Universidad de Ibague - Electronica Digital II

-Diego Alejandro Torres Urrego (https://github.com/Diegollmll)
-Luis Fernando Gomez Diaz
