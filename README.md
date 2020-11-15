## Introduction

This repo contains the code to read the PMS5003 sensor using Arduino, it is mostly adopted from this [great tutorial](https://how2electronics.com/interfacing-pms5003-air-quality-sensor-arduino/). Instead of using Arduino Uno (mine is used in another project), I just used a MEGA 2560 instead. It is mostly the same, there is only one difference, that I have to use pin 10 and 11 instead of 2 and 3 as suggested by the tutorial. By reading the limiations on the [SoftwareSerial page](https://www.arduino.cc/en/Reference/SoftwareSerial), I found the pin 2 and 3 need to be replaced.

```
Not all pins on the Mega and Mega 2560 support change interrupts, so only the following can be used for RX: 10, 11, 12, 13, 14, 15, 50, 51, 52, 53, A8 (62), A9 (63), A10 (64), A11 (65), A12 (66), A13 (67), A14 (68), A15 (69).
```

I won't go into the details as the original tutorial is very clear. Here is a picture for my sensor.
![Example](./img/setup.jpg)

