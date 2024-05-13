# GC Nano
<img src="https://github.com/CrazyGadgetMods/GC-Nano-Suite/blob/main/images/nano.png" height=600>

This repo contains the suite of custom PCBs required to build the GC Nano v1 / v1.1, with the exception of the [PSU-Plus](https://github.com/CrazyGadgetMods/PSU-Plus). All 3D model files (as well as a more formal release post) can be found in the [GC Nano - The Worlds Smallest Gamecube](https://bitbuilt.net/forums/index.php?threads/gc-nano-the-worlds-smallest-gamecube.5697/) thread on the BitBuilt Forums.

## Top Board
- USB type C port with 5.1k ohm resistors on each of the CC lines to enable any Power Delivery (PD) compliant charger to output 5V @ 3A.
- MAX16054 Push-On / Push-Off IC paired with a PFET to turn the system on and off with a single tact switch
- GL823K Micro SD to USB converter IC.
- USB MUX - when the system is off, the USB data lines connect to the USB-C port, allowing file transfer without having to open up the case; when the system is on, the USB data lines go to two pads which get soldered to the Wii.
- Sync and Reset buttons to be soldered to the bluetooth module / Wii.

## Controller Board
- Solders right to the TRRS jacks, eliminating the need for any daisy-chain hand-wiring between the ports.
- Three power pads are wired to the complimentary set on the top board for clean assembly.
- Data lines get wired to the Wii
- Incorporates pull-up resistors for the data lines, as the original resistor array is cut off for the OMEGA trim.

## HDMI-FFC
- Allows us to mount the HDMI port to the back handle, as well as interface it with the AVE-HDMI via an FFC cable.

## Credits
- [Wesk](https://bitbuilt.net/forums/index.php?members/wesk.1486/): Inviting me to collaborate on the GC Nano project, creating the GC Micro
- [Madmorda](https://bitbuilt.net/forums/index.php?members/madmorda.554/): Creating the original [World's Smallest Gamecube](https://www.youtube.com/watch?v=_BxwS_uTKt4)
- [YveltalGriffin](https://github.com/mackieks): Advice while designing the Top Board / PSU-Plus
- [BitBuilt](https://bitbuilt.net/): Being the best modding community out there!

## License
Solderpad Hardware License v2.1