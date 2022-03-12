# pummer

The MicroPower SE 
this is a raw copy of this page
credit to : http://solarbotics.net/library/circuits/se_t1_micropwr.html

A 'micro power solar engine' has been a goal since my introduction to BEAM Robotics.
I believe that if there wasn't one before, I there is one now. What I'm presenting to you looks very similar 
to one of the circuits found in Steven Bolt's web pages. As you will see, I made only minor changes to that design and not without help. 
My contributions have been to recognize the potential of the circuit , bread board and test it. 
The bottom line is that if you have a power source which will provide 2.5Vdc at 10uA this circuit should drive a pager motor. 
It turns on the motor at 2.3 to 2.5Vdc and switches off at 1.2 to 1.5Vdc.

The bottom line is that if you have a power source which will provide 2.5Vdc at 10uA this circuit should drive a pager motor. 
It turns on the motor at 2.3 to 2.5Vdc and switches off at 1.2 to 1.5Vdc.

![micropower_se2.jpg](/Pict/micropower_se2.jpg)

And here are Ken's comments (slightly edited) on the design changes:

There have been two optional changes.
The first results from building a number of units. It was found that R1 could be replaced with a 680K resistor rather than using a pot. R6 was added to limit the current used to drive the base of Q4 which meant that more current became available for the motor. 390 Ohms is the smallest value that should be used for R6, it can be larger depending upon the motor and drive transistor (Q4) combination.

There is one further proposed change that could improve the overall efficiency but it has not been tried, as far as I know. Changing Q4 to a ZTX618 improves the voltage across the motor. It is manufactured by Zetex and available from Digi-Key, but the trouble and the price ($1.08 US) may just not be worth it.
