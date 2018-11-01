# CNC-sphere-o-bot

The Arduino code has been modified to work with a standard Arduino CNC V3 shield. The pin declarations have been modified from the original source because the CNC shield utilizes different pins than the shield this code was orgininally written for.  The original pin declarations appear (as remarks) in the code for reference.

The stepper drivers should be plugged into the X and Y sockets on the shield with the X driver connected to the rotation stepper, and the Y driver connected to the pen stepper.

The servo that lifts the pen should be connected as follows: 
ORANGE--> +5V, BROWN--> GND, YELLOW--> Z+ End Stop
