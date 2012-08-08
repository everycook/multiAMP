This layout is a amplifier board for Arduino and similar microcontroller boards.

It has four channels but you can easily cut it to one channel or copy it to add more channels. 
The Vcc and Gnd rails on top and bottom are designed for this modularity.

Its amplifies the signal of a load cell or any other bridge circuit sensor. 
It has active noise filtering for improving the signal quality.

It is designed around the National Semiconductor LMC 6482 in SO8 package. 

Gain and offset are fine-tuneable over a wide range so you will be able to use it with many sensors.
You can either use trough-hole trimmers with bent legs (cheaper) or SMD trimmers (smaller).

The zener diode limits the output to 3.3 Volts. If you want 5V and run the board with 5V you can remove it. 

If you run the board at higher voltages to get a higher excitation of the sensor bridge you may have to put in another zener diode to protect the ADC input of you microcontroller.

For now there is only a layout for the copper layer with all text etched directly into the copper. 

The layout is single-sided SMD. No drilling required.

Feel free to add silkscreen and soldermask. 
