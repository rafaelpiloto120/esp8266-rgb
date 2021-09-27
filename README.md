# Projet Crypto Night Light Led
Very simple project with Neopixel for D1 Mini ESP8266. It is based on the Adafruit Neopixel library.

The goal is basically to set a color and brightness to a WS2812B led.

## Electronics
1x Wemos D1 Mini (or any ESP8266 with 4Mb Flash)

1x WS2812b RGB Led

1x Wires (3 cores, about 3-4cm)

1x Micro USB Cable and 5V Power supply

## Cables assemble
This is one the key steps. Please sure you connect the cables correctly between the Wemos D1 Mini and the WS2812b RGB Led

![Image of ESP8266 to WS2812b RGB Led connections](https://github.com/rafaelpiloto120/esp8266-rgb/blob/main/Screenshot_1.png)

## Printed Parts
The models to be 3D printed can be found here:  https://www.thingiverse.com/thing:2974862

## The Arduino IDE

To code and upload code for the Wemos D1 Mini, use The Arduino IDE.

1. Download/Clone this Repository and unpack it on your favourite folder

2. Download and install the latest version of the Arduino IDE for your system https://www.arduino.cc/en/Main/Software

3. Add ESP Board Manager to your IDE : Therefore open File>Preferences After "Additional Boards Manager URLs" insert: http://arduino.esp8266.com/stable/package_esp8266com_index.json

![Configure ESP8266 in Arduine IDE](https://github.com/rafaelpiloto120/esp8266-rgb/blob/main/001.png)

4. Then open Tools>Board>Boards Manager Search for ESP Install latest ESP8266 Board Manager
ddd

5. Add Additional Libraries Therefore open Sketch>Include Library>Manage Libraries... Search for Adafruit Neopixel Install latest Adafruit Neopixel library


* Restart Arduino IDE
* Choose your board and com port
* Upload




