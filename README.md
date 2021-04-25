# AriloSprinkler-Hardware
OpenSprinkler ESP32-WROOM Hardware Design variant including a Lora E22-900M30S-SX1262 and made in Kicad software.

HW features:
- 8 valve AC driver compatible with OpenSprinkler Zone Expanders
- Lora E22-900M30S-SX1262 long range transceiver (up to 30dBm)
- USB interface for debugging/flashing
- Ethernet interface (Exemplary module: https://de.aliexpress.com/item/2042562851.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- RF Transmitter interface (Exemplary module: https://de.aliexpress.com/item/4001119703303.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- Compatible with DIN rails (Used holding system: https://de.aliexpress.com/item/32827395562.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- Reworked current measurement with inverted precision rectifier required due to the ADC of the ESP32
- RTC
- Button switches

Tested features:
- Opensprinkler SW features work
- Lora transceiver works
- Current measurement works
- Valve control works
- Button switches work

All parts have a LCSC reference number and are at the time of writting this readme available in the JLCPCB SMT library. I have got my prototype boards produced by JLCPCB (quite inexpensive, 5 full SMT assembled and shipped PCB's for arround 75€, additionally E22 module, ESP32 and USB and SMT connectors to be added and soldered).

The compatible SW can be found in the following OpenSprinkler Firmware branch:
https://github.com/arijav/AriloSprinkler-Firmware

Note: This is a home made prototype. No guarantee of any kind is given. If you want a commercial product please order the regular OpenSprinkler official parts.

Final design (not yet produced, use at your own risk):

![Final design front](https://github.com/arijav/AriloSprinkler-Hardware/blob/master/AriloSprinkler/Pictures/AriloSprinklerAC_front.jpg)
![Final design back](https://github.com/arijav/AriloSprinkler-Hardware/blob/master/AriloSprinkler/Pictures/AriloSprinklerAC_back.jpg)

Prototype:

![Prototype front](https://github.com/arijav/AriloSprinkler-Hardware/blob/master/AriloSprinkler/Pictures/AriloSprinklerAC_prototype_front.jpg)
![Prototype back](https://github.com/arijav/AriloSprinkler-Hardware/blob/master/AriloSprinkler/Pictures/AriloSprinklerAC_prototype_back.jpg)

For questions send a message to:
gmail email: arijav2020
