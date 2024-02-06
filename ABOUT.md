
This project follows up my previous [iot_leddriver_hw](https://github.com/0xjmux/iot_leddriver_hw) project, which was designed to control 5V WS2812B strips. 
It worked well, but I wanted to also be able to control the single color strips I had lying around, and wasn't able to find a suitable driver to do so. 
So, I set out to develop my own. 


#### Project Design Goals
When undertaking this project, I had the following goals in mind:
1. Low-cost and hand-assembleable, with a BOM goal of under $10.
2. Compact design, easily stowed away and hidden from view. Thoughtful system design, all ports on one side of PCB. 
3. Setting up the board with an LED strip must be self-explanatory for "non-technical" people, and the system design should guide them away from mistakes that result in hardware damage. 
4. Board must be safe on its own and should protect against problems with connected strips. This meant circuit protection, from both overvoltage and shorts.
5. Wi-Fi connected using ESP module, and compatible with WLED for easy control and integration with existing setups. 
6. Should be able to control any type of "dumb" 12V strip, from single color to RGBW



#### Project TODO:
* convert to ESP32-C3 - right after I ordered my first set of boards WLED 1.14 came out, and they're deprecating ESP8266 support. Whoops. 
* fix coil whine from power mosfet drivers
* 
