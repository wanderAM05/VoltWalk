Problem Statement:
Not enough accessible energy generating resources available to the general public

Idea:
From the POV of a common Indian neighbourhood. Community parks and playgrounds are where people come together to have fun, exercise, and most importantly, make productive use of their pent-up energy. Our team visualised this space where we can transform the energy people use while walking, and the energy that children use while playing.

Prototypes and rejected versions:
We explored the concepts of a trampoline where the springs were replaced with pistons that had solenoids in them, and a playmat with piezoelectric sensors that would generate energy when stepped on, creating paper prototypes for both. Finding the trampoline too complex for little output, we opted for the mats. Initially, we had trouble with the elecricity generation, as it was too spontaneous, and the values of voltage were constantly changing.

Final project idea:
In the end, we decided to use a full-wave bridge rectifier to convert the alternating current into direct current (at the cost of some lost energy).We decided to make a stack of foam on each of them, which played a role in protecting them from large direct forces. Then, we placed a mat on the top and bottom of these sensors, which allowed even distribution of force to each sensor. We placed each of the piezos in parallel in our final circuit so that the circuit doesn't becomes worthless if any connections break, and so that the value of voltage is constant (whenever pressure is applied on the piezo). 

Objectives of the project:
Build a prototype of electricity generating piezoelectric tiles ('VoltWalk') using a grid of piezo sensors connected in parallel.
Layer/enclose the circuit between EVA foam tiles to create a more seamless (and aesthetic) design for the tiles. 
Generate an average of 5V (DC), which is enough to charge a standard phone. 
Imply how VoltWalk can be scaled up to environments which receive more foot traffic, where the tiles can sustainably generate enough electricity to airports, train stations, etc (where they are implemented).

Materials:
40 piezoelectric sensors (35mm piezos; 27mm piezos)
4 EVA foam tiles (1 foam tile = 1ft x 1ft)
Jumper wires
2 metres of copper wire
LEDs (for demonstration)
4 breadboards

Assembly and debugging:
We first assessed the 35mm and 27mm piezoelectric sensors to see how much voltage they can generate individually, to gain a better understanding of how we can arrange the piezo sensors. We built (and rebuilt) the full-wave bridge rectifier circuit to convert the AC produced by the piezoelectric sensors to DC. Then, we divided our sensors across two mats-- building the 1.2" legs on top of each piezoelectric sensor out of sunboard. Our final circuit consisted of the positive ends and negative ends of each sensor being soldered to their respective ends in the full-wave bridge rectifier circuit. We hot-glued the tile shut, so that it can be stepped on easily, distributing the force (when stepped on) evenly. 
