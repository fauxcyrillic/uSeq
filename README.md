# uSeq
RP2040-based LISP liveprogramming module


A conversion of the Eurorack module by Emute Lab Instruments: https://www.thonk.co.uk/shop/emute-lab-useq/

THIS IS NOT TESTED. I have not built this module. I did the whole board layout and panel in burst of inspiration in late 2024, then my attention got drawn to other things. So: *I do not know if this works properly*, although I did a pretty careful job of adapting the schematic. Someone may wish to take the plunge, or pull it apart and use this as a base to build their own version. Seems silly to leave it just sitting on my hard drive though.

The board cutouts and extra headers in the bottom left are for a USB-C breakout board. I planned it for this: https://thepihut.com/products/sparkfun-usb-c-breakout-vertical

The idea was that this breakout board would sit *underneath* the main PCB, with the headers pointing "down" to connect the two, and protrude through the PCB and then through the frontpanel. From my hasty measurements, I figured the extra few mm will leave the USB-C socket more or less flush with the panel, rather than sticking out awkwardly. I measured it pretty carefully, so the cut-throughs should be big enough and in the right place, but again, no guarantees.

![3D_PCB1_2024-10-30](https://github.com/user-attachments/assets/a509f5ad-cddf-4282-956b-ad93020ed47c)

