# PlanetMassToCarveDebrisGap

Python program to calculate the gap carved by a planet embedded in a
massive debris disc, by Tim D. Pearce. The model is described in 
Friebe, Pearce & Lohne 2022, and produces a figure akin to their Fig. 5.
The main difference to conventional gap width estimates (which use e.g. 
the Wisdom overlap criterion) is that, if the debris disc has mass, then
an embedded planet would migrate as it scattered debris. This means that 
a low-mass, strongly migrating planet could carve as wide a gap as a 
high-mass, barely migrating planet. Given the parameters of the star, the
disc edges, the central location of a gap, and the (pre-interaction) 
debris disc mass, the program plots gap width as a function of the mass 
of an embedded planet. Additionally, if a target gap width is provided by
the user (optional), then the program returns the parameters of the 
possible planets that could carve that gap. 

To use the program, first download and unpack the ZIP file (press the green 'Code' button on GitHub, then 'Download ZIP', then unzip the file on your computer). Then simply run planetMassToCarveDebrisGap.py in a terminal.

The default settings are for HD 107146. To change the parameters, change the values in the 'User Inputs' section of planetMassToCarveDebrisGap.py (you should not have to change anything outside of that section).

IMPORTANT: The model assumes that the interaction has finished, i.e. the 
planet has stopped migrating. If instead migration is still ongoing, then
the disc gap would widen in time and these results could be invalid (see 
Sect. 3.3 in Friebe, Pearce & Lohne 2022 for ways to check and account 
for this).

Feel free to use this code, and if the results go into a publication,
then please cite Friebe, Pearce & Lohne 2022. Finally, let me know if you
find any bugs or have any requests!
