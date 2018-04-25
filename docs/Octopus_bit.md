## Introduction

ELECFREAKS Octopus:bit is a kind of breakout boards for micro:bit. It can lead out GPIO port, serial port, IIC port, and SPI port on the micro:bit board. The biggest feature of Octopus:bit is that it can switch electric level for some GPIO ports, which makes micro:bit available to be adapted to 5V sensors.


![1](https://www.elecfreaks.com/wp-content/uploads/2018/01/1_EN.png)


## Hardware

### Features

- Input voltage: 3.3V（powered by the edge connector of micro:bit）
- Extend all of GPIO ports(P0~P16, P19~P20).
- Beneath each I/O port, there are pins for VCC and GND. These pins are differentiated by different colors, which enable you to connect your extension module easily. The spread of pins is fully compatible with Octopus series' products.  
- With a voltage boosting module, you can shift the working voltage of P8, P9, P11~P16 between 3.3V and 5V through the voltage switch. 
- When the voltage switch is at the end of 3.3V, the max current of octopus:bit depends on its power method. When powered by USB port, the output current is 90mA; when powered by PH2.0 battery port, the output current depends on the battery power ability. 
- When the voltage switch is at the end of 5V, the maximum output current of 5V part is 500mA.
- Lead out serial port, I2C port and SPI port, among which I2C can connect 3 channels of I2C devices and SPI can connect 2 channels of SPI devices. 
- Available for direct serial port communication between two breakout boards. 


### Application

It is suitable for all conditions that require micro:bit GPIO such as programming education, smart device creation, and so on.  

### Pins & Connectors

![2](https://www.elecfreaks.com/wp-content/uploads/2018/01/2-2.jpg)


### More Details 
#### Standard GVS Port 

![3](https://www.elecfreaks.com/wp-content/uploads/2018/01/3-2.png)

Among the standard GVS ports, the working voltage of the yellow part（P0~P7， P10）is 3.3V, while the working voltage of the blue part（P8, P9, P11~P16）can be shifted between 3.3V and 5V through a voltage switch. 
Beneath each I/O port, there are pins for VCC and GND. These pins are differentiated by different colors, which enable you to connect your extension module easily. The spread of pins is fully compatible with Octopus series' products.

#### Voltage Switch 

![4](https://www.elecfreaks.com/wp-content/uploads/2018/01/4-1.png)

Sliding this switch, we can change the voltage of the blue IO ports（P8, P9, P11~P16）between 3.3V and 5V.

You can see its working range in the below: 

![5](https://www.elecfreaks.com/wp-content/uploads/2018/01/5-1.png)

#### Serial Port

![6](https://www.elecfreaks.com/wp-content/uploads/2018/01/6.png)

The working voltage of serial port is available to be shifted between 3.3V and 5V through the voltage switch. 
Redirect TX to P8，RX to P12. The left pins are bidirectional serial port, which can run both input and output. The right female header is a one-way output serial port. 
**Note** : To use this port, we have to initialize it according to the program in the below: 

![7](https://www.elecfreaks.com/wp-content/uploads/2018/01/7-1.png)


### Dimension 

![8](https://www.elecfreaks.com/wp-content/uploads/2018/01/8.jpg)


## Software
### Example 1 Music Broadcast
#### Hardware Connection 
Connect passive buzzer module to PO.

![9](https://www.elecfreaks.com/wp-content/uploads/2018/01/9.jpg)

#### Code Example  

![10](https://www.elecfreaks.com/wp-content/uploads/2018/01/10-2.png)

Code Link：[https://makecode.microbit.org/_fAmC3WERHdR2](https://makecode.microbit.org/_fAmC3WERHdR2)

Download the whole program into your micro:bit, the buzzer will play Happy Birthday again and again in round.  


## Relative Cases 

[Intruder Detection](https://www.elecfreaks.com/9455.html)  
[Fish Feeder](https://www.elecfreaks.com/9441.html)  
[Plant Humidity Monitor](https://www.elecfreaks.com/9363.html)  
[Burglar Alarm Device](https://www.elecfreaks.com/9572.html)   
[Motion Detector](https://www.elecfreaks.com/9643.html)   
[A Smart Light](https://www.elecfreaks.com/10089.html)  
[Music Machine](https://www.elecfreaks.com/10250.html)   
[Lie Detector](https://www.elecfreaks.com/10340.html)  
[Avoide the Asteroids](https://www.elecfreaks.com/10475.html)  
[Maze Runner](https://www.elecfreaks.com/11887.html)   
[QUICK MATHS](https://www.elecfreaks.com/12250.html)  
[Electro-Theremin](https://www.elecfreaks.com/11084.html)  
[A Micro:bit Car](https://www.elecfreaks.com/11330.html)  
[Flipping Pancakes](https://www.elecfreaks.com/11784.html)  
[Micro:bit Game: Pitch Perfect](https://www.elecfreaks.com/12328.html)  


## Relative Components


### [BBC micro:bit](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)

[![13](https://www.elecfreaks.com/wp-content/uploads/2018/01/13.png)](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)


### [Octopus Bricks Series](http://www.elecfreaks.com/estore/octopus-bricks-sensor)

[![14](https://www.elecfreaks.com/wp-content/uploads/2018/01/14.png)](http://www.elecfreaks.com/estore/octopus-bricks-sensor)

#### [ElecFreaks Micro:bit Tinker Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-tinker-kit.html)

[![15](https://www.elecfreaks.com/wp-content/uploads/2018/01/15.jpg)](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-tinker-kit.html)
