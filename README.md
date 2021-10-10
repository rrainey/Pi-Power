# Pi-Power for DSKY-matic

This is an integrated power supply for the DSKY-matic.  It supplies 5VDC for the
Raspberry Pi, keyboard, and alarm modules. It also supplies either +3.3VDC or +7VDC for the Display module, depending on whether you are using the LED or EL variant of that module.

Takes power from a 9-24VDC power adapter. I am testing the DSKY-matic using a TRIAD model WS8U090-2000; 7VDC 2.0A.

PCB based on the original Pi-Power project from Tonymac32. I added a separate +3.3 VDC section to the original +5 VDC-only design.

![Image](images/board.PNG "board")

## A Warning from the original author

Do not stick your fingers into this circuit while it's powering 
something you care about.  
Your fingers have a resistance value, and will change the feedback network regulating the output circuit, potentially 
causing a power surge.  
