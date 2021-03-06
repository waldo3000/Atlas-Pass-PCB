# Atlas Pass v4 PCB
A custom PCB designed to look like a No Man's Sky Atlas Pass v4

To order one, download the "ap4_gerbers.zip" file and upload it to a PCB vendor.
For seeedstudio.com, for example, go to https://www.seeedstudio.com/fusion_pcb.html, click "Add Your Gerber File", upload the ap4_gerbers.zip file, then set the following:

PCB Color: White (this makes the board white instead of green)

Surface Finish: ENIG (this makes the metal portions gold instead of silver)

All other options can be left as their defaults

=========================================================

LED Lighting

If you wish to make the Atlas Pass light up when plugged into a USB port, do the following:
* Solder a LED to the pads in the center of the Atlas symbol.  Rotate it so that the cathode (end with the green dot) is up when the "G-17" text is right-side up.
* Solder a 1K resistor to the pads just below the USB connector. Either polarity is OK.
* Apply two layers of electrical tape to the back side of the PCB where the USB connector is.  This provides the proper spacing to ensure the USB contacts make a connection with the USB cable.  It is possible to order a 2.0 mm thick PCB instead, but that is much more expensive.
* Since the USB connector is recessed, you must use a USB extension cable to supply power to the card.
* LED: Digi-Key part number: 732-4978-2-ND
* Resistor: Digi-Key part number: P1.0KGCT-ND 

