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

# Firmwarre
Firmware is still work in progress.

Latest can be found here:
https://github.com/patrickjahns/esp_rgbww_controller_fw

# Modifying

The schematic and board files are compatible with eagle 7.2+

## Ideas
Here are some ideas for future revisions
- connect ADC to detect powerfailure 




