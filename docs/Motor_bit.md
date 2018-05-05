## Introduction
ELECFREKAS Motor:bit is a kind of motor drive board based on micro:bit. It has integrated a motor drive chip TB6612, which can drive two DC motors with 1.2A max single channel current. Motor:bit has integrated Octopus series’ sensor connectors. You can plug various sensors into it directly. Among these connectors, P0, P3-P7, P9-P10 support sensors with 3.3V power voltage only; P13-P16, P19-P20 support 3.3V or 5V sensors. You can change electric level by sliding the switch on the board.

##Introduction

[ELECFREKAS Motor:bit](http://www.elecfreaks.com/estore/elecfreaks-motor-bit-for-micro-bit.html) is a kind of motor drive board based on micro:bit. It has integrated a motor drive chip TB6612, which can drive two DC motors with 1.2A max single channel current. Motor:bit has integrated Octopus series' sensor connectors. You can plug various sensors into it directly. Among these connectors, P0, P3-P7, P9-P10 support sensors with 3.3V power voltage only; P13-P16, P19-P20 support 3.3V or 5V sensors. You can change electric level by sliding the switch on the board.

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/1-1.jpg)


## Hardware 

### Features:

Motor Drive Chip: TB6612
Support GVS-Octopus electric Bricks' connector
Some GVS connectors support electric level switch between 3.3V and 5V.
With 2 channels DC motor connectors, max single channel current is 1.2A.
Input Voltage: DC 6-12V
Dimension: 60.00mm X 60.10mm
Weight: 30 g

### Application:

It is compatible with [ElecFreaks Octopus electric bricks module series](http://www.elecfreaks.com/estore/octopus-bricks-sensor) due to its built-in 3 pin IO electric brick GVS extension connector.
It can be used as the development board of mini smart cars and balance cars.
Users can develop mobile-controlled robot, robot arms, etc..

### Connector Information:

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/2.jpg)

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/000.png)

###Detailed Introduction Of Some Connectors：

**1.VCC Switch-3.3V/5V electric level switch.**

Slide switch to the end of 5V, the electric level of the blue pins (P13、P14、P15、P16、P19、P20) on motor:bit is 5V, and the voltage of the red power pins is 5V too. Similarly, when slide switch to 3.3V, the voltage of blue pins and red pins are 3.3V.

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/3-1.jpg)

**2.Digital Pin Connector.**

Digital pins: P4、P5、P6、P7、P9、P10.

G-3V3-S connector: 3V3 stands for 3.3V power voltage, G is for GND, S is for signal. GVS is a standard sensor connector, which enables you to plug onto servos and various sensors conveniently. At the same time, it supports our [Octopus Bricks series'products](http://www.elecfreaks.com/estore/octopus-bricks-sensor).

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/4.jpg)

**3.3.3V/5V dual electric level GND-VCC-SIG connector：P13, P14, P15, P16, P19, P20.**

The specialty of G-VCC-SIG connector lies in that it can support 3.3V or 5V power device by shifting electric level of 3.3V/ 5V through VCC connector. At the same time, it supports our [Octopus Bricks series' products](http://www.elecfreaks.com/estore/octopus-bricks-sensor).

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/5.jpg)

Motor Input Connector: Two motor input connectors in total. M1+, M1- and M2+, M2- separately controls a channel of DC motor.

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/6.jpg)

M1，M2 Motor Control Instruction: P8 and P12 relatively controls the rotating direction of M1 and M2; P1 and P2 control motor speed.

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/0001.png)

## Dimension:

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/7.jpg)

## Example

###Hardware Connection
Please connect components according to the picture below:

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/8.jpg)

### Programming
Positive Rotation of Motor:

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/9.jpg)

P8 in high electric level means the positive rotation of motor. You can adjust the logic value of P1 to control motor speed.

Negative Rotation of Motor:

![](https://www.elecfreaks.com/wp-content/uploads/2018/04/10.jpg)

P8 in low voltage level means the negative rotation of motor. ou can adjust the logic value of P1 to control motor speed.

If you need more cases about micro:bit, please keep watching our blogs posted on [https://www.elecfreaks.com/blog](https://www.elecfreaks.com/blog).


## Relative Cases:

[Make A Cool Micro:bit Hovercraft Together](https://www.elecfreaks.com/11518.html)

[Create a Line Follow Car with Micro:bit](https://www.elecfreaks.com/12181.html)
