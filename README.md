# RS485RGB-light

A simple Arduino / atmega328p based platform to drive ws2812b led strips over rs485 for musical lighting purpose.

The main controller board works as an Arduino Mega shield and offers a DMX (rs485) in and out to communicate with a larger light system, an RS485 line to comunicates with the slave boards that drives the leds, an audio line with an MSGEQ7 which is a seven band graphic equalier to use the system as standalone and an oled color display.

The slave boards are based on the arduino nano.

https://easyeda.com/gregoiremerien/lt-rgb-master
https://easyeda.com/gregoiremerien/lt-rgb-smd

![Image](https://github.com/GMerien/RS485RGB-light/blob/master/IMG_20200528_141512.jpg)
![Image](https://github.com/GMerien/RS485RGB-light/blob/master/IMG_20200528_141458.jpg)
