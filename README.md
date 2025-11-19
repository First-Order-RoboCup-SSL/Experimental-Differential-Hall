# Experimental-Differential-Hall

PCB files for an experimental differential (dual) Hall element sensor. This PCB will attach to an STM32 which will perform processing on the output signals, so this PCB takes the Hall elements' output and ensures that the swing will use the maximum part of the 0-3V3 the STM32 can accept for SNR.

Still need to minimise resistors and power usage around our 5(?)% tolerance for resistors and then route PCB, but the amplifier (assuming +-370mV around "ground" (2V) seems to work in LTSpice.

Takes in 3V3, GND, and 5V because the Hall element AFAIK wants +-2V around "GND".
