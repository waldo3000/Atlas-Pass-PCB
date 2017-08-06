# Atlas-Pass-PCB
A custom PCB designed to look like a No Man's Sky Atlas Pass v4

To order one, download the "ap4_gerbers.zip" file and upload it to a PCB vendor.
For seeedstudio.com, for example, go to https://www.seeedstudio.com/fusion_pcb.html, upload the ap4_gerbers.zip file, then set the following:

PCB Color: White
Surface Finish: ENIG

All other options can be left as their defaults

=========================================================

LED Lighting

If you wish to make the Atlas Pass light up when plugged into a USB port, do the following:
* Solder a LED to the pads in the center of the Atlas symbol.  The cathode (end with the green dot) is up.
* Solder a 1K resistor to the pads just below the USB connector. Either polarity is OK.
* Apply two layers of electrical tape to the back side of the USB connector.  This provides the proper spacing to ensure the USB contacts make a connection with the USB cable.  It is possible to order a 2.0 mm thick PCB, but it is much more expensive.
* Since the USB connector is recessed, you must use a USB extension cable to supply power to the card.
* LED: Digi-Key part number: 732-4978-2-ND
* Resistor: Digi-Key part number: P1.0KGCT-ND 

