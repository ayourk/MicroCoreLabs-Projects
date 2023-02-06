# EPROM_Emulator/PCB
EPROM Emulator - Small PCB which uses [Teensy 4.0](https://www.pjrc.com/store/teensy40.html) to emulate up a 64KB 27C512 EPROM

![ROM_Emulator front](ROM_Emulator-front.png) ![ROM_Emulator back](ROM_Emulator-back.png)

This is PCB was designed in KiCAD 6.10 and uses MicroCore Lab's EPROM Emulator as a base.  All traces were redone and 2 solder jumper pads were added to the front along the right side of the board to make the board Chip Select(CS) pin configurable.

The Nabu uses Pin 20 for Chip Select (lower solder jumper) and the IBM PC uses the Pin 22 for Chip Select (upper solder jumper) which is what the board was originally designed for.

Please solder closed the appropriate solder jumper pads before use. Neither solder jumpers are connected by default!

Per the Build of Materials, in addition to the PCBs, you will want:

1. [Teensy 4.0](https://www.pjrc.com/store/teensy40.html) which is the workhorse of this project.
2. [IC Header](http://store.go4retro.com/ic-header/) which is top/bottom jumper pins in IC socket form.
3. 3x Bus Transceivers via either [Digikey](https://www.digikey.com/en/products/detail/texas-instruments/SN74LVT245BDBR/373941) or [Mouser](https://www.mouser.com/ProductDetail/Texas-Instruments/SN74LVT245BDBR?qs=FM6NhYOeeBVRIGHSKl2GVg%3D%3D). I couldn't find the equivalent in stock via [LCSC](https://www.lcsc.com/search?q=SN74LVT245BDBR) so that they could be surface mounted via JLCPCB. :frowning_face:

