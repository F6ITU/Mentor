# Mentor

Kicad files

An Arduino based SSPA display controler for HPSDR/Hermes familly
This module controls 
- voltage
- current
- temperature
- VSWR/PWR
- cooling fan
- 4x40 lcd display
and shuts down the Bias current while beeping in case of dificulties

This board and the associated firmware have been developped by ON7EQ. 

http://www.qsl.net/on7eq/projects/arduino_sspa.htm

Some code modifications have been made by John Melton for 
the Hermes familly.

The design of this board uses the generic output names
used by all Hermes/Angelia boards and could directly be plugged 
on the Alexandrie control board

So far, NO SSPA and NO Reflectometer/Refl-fwd coupler have been
designed. A multipurpose 33dB Tandem Match coupler
is under development (for both VSWR/PWR measurement and 
predistorsion -aka "pure signal"- sampling)


Board's dimensions are oversized to fit the 5x10 and 10x10cm 
size of all board of the Hermes project under Kicad: 

AlexI2C

Alexandrie 

Alexiares_Coax_Out

Alexiares_HPF

Alexiares_LPF

Mentor(this one)



