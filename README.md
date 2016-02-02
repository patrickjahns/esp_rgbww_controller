# ESP8266 WiFi RGBWW LED Dimmer
Custom Hardware board for controlling 5 Led Channels via PWM (RGB + Warm/Cold White). It is designed for max current ~4.5A per Channel.

# Parts
- 1x ESP8266, ESP-12 format
- 1x XM1584 Power converter (set to 3.3v!)
- 5x IRLZ44N Mosfet (logic level gate threshold)
- 8x 10k resistors, 0603 format
- 1x 470 µF Elko RM 3.5 mm 
- 1x 5,08mm 2pin terminal block
- 1x 5,08mm 3pin terminal block
- 1x 5,08mm 4pin terminal block
- 1x 2,54mm 4pin header
- 1x Micro SMD Tact Switch 2 pin 3*6*2.5 mm 

# Software
Work in Progress. The idea is to design a custom firmware that will interface with fhem (http://fhem.de/) to allow advanced controlling of the LEDs.
The idea is to render color transitions on the esp. (Instead of sending individual colors for transitions). 
Also we wish to include certain scenes (sunrise, sunset, candle light) into the controller

Discussion is here:
http://forum.fhem.de/index.php/topic,34464.0.html (German)

# Modifying

The schematic and board files are compatible with eagle 7.2+


