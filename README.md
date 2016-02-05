# ESP8266 WiFi RGBWW LED Dimmer
Custom Hardware board for controlling 5 Led Channels via PWM (RGB + Warm/Cold White). It is designed for max current ~4.5A per Channel.

# Parts
- 1x ESP8266, ESP-12 format
- 1x XM1584 Power converter (set to 3.3v!)
- 5x IRLZ44N Mosfet (logic level gate threshold)
- 8x 10k resistors, 0805 format
- 1x 470 µF Elko RM 3.5 mm 
- 1x 5,08mm 2pin terminal block
- 1x 5,08mm 3pin terminal block
- 1x 5,08mm 4pin terminal block
- 1x 2,54mm 4pin header
- 1x Micro SMD Tact Switch 2 pin 3*6*2.5 mm 

For ADC power Failure add:
- 1x 10k resistor, 0805 format
- 1x 1k resistor,0805 format
change C1 from 470 µF to at least 1000µF (still RM 3.5mm)

# Assembly
Assembly of the PCB Board is straight forward, solder all parts to the PCB.

__Caution :__ before soldering the esp module to the PCB, set the output voltage of XM1584 converter  to 3.3v

### Recommended steps
- Start with soldering the smd resistors
- __Ensure the output voltage of XM1584 converter is 3.3v before continuing__. 
- Solder the XM1584 Power Board 
- Solder ESP8266 Module 
- Optional: solder SMD Tact Switch
- Solder Elko
- Solder Terminal Blocks, 4pin header 
- Solder FETs


# Firmwarre
Firmware is still work in progress.

Latest can be found here:
https://github.com/patrickjahns/esp_rgbww_controller_fw

# Modifying
The schematic and board files are compatible with eagle 7.2+

## Ideas
Here are some ideas for future revisions
- ~~connect ADC to detect power failure~~ => Done v1.1


# Resources

* [ESP RGB Project](https://github.com/RiRomain/esp-dimmer-hardware)
* [H801 Wifi Controller Hack](http://chaozlabs.blogspot.de/2015/08/esp8266-in-wild-wifi-led-controller-hack.html)


# Credits
Thanks to RiRomain for his excellent documentated [ESP RGB Project](https://github.com/RiRomain/esp-dimmer-hardware)


