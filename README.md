# Schakelaar
Voltage Controlled 3 position switch Eurorack module.

3 inputs selected by the position CV input (< -1.7 volt selects the bottom input, > +1.7 volt selects the top input and else the middle is selected.
position input's normal is a counter that can by clocked by an input or the push button and has a reset input.
position input has a mult so you can send it to another switch or other modules.

## chip
Make sure to use 20v CD4052 version like TI chips, because some other variants only accept maximum of 15 volts. My circuit uses 17 volts, -12 to 5v. Better not to buy the chips from aliexpress or eBay because often they mix up all the different types, like they are the same. TI CD4052BM96

## Aluminium front panel
The reason I choose aluminium as material for the front panel is because it is recyclable. PCB (FR-4) material is not recyclable.
I also tried wood panels, I like them. But it takes a more efford to print on. I will also try Acrylic one day, just to try. It is better then FR-4 but I think less well for the environment as Aluminium.
The front panel is a single layer "circuit" on aluminium with white soldermask. The jacks and switches have a space around without soldermask, so the panel is grounded.

I made the text really small, because I think it is less usefull after a while. It is more like a manual.

## The Animal Illustration
Instead of asking AI to "generate" me a representation that is not a robot, I picked the nicest donkey from the "Lets Draw It" website https://letsdraw.it/
