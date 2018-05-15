![8](https://i.imgur.com/DuxosEs.jpg)

## Introduction
---
Servo is a kind of driver for position (angle) servo. It is suitable to control system with constant angle change and can remain its status. In this experiment, we are going to use Micro:bit to make a servo rotate circularly within a travel range. 


## Component List  
---
### Hardware：  
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [microbit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x TowerPro SG-90 Mini Servo(1.6kg)  
- 1 x [Breadborad Jumper Wire 65pcs Pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  

**Tips: If you want all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html). **  
 
### Software:  
Microsoft Makecode Online Editor  

## Major Component Introduction  
---
### Servo  
Servo is a set of automatic control system, which consists of DC motor, reduction gear unit, potentiometer and control circuit. It can define rotate angle of output shaft by sending signals. Usually, a servo has a maximum rotate angle(e.g. 180 degrees). Compared with ordinary DC motor, servo rotates within a certain angle range only while ordinary DC motor rotates in circle. This is the major difference between ordinary DC motor and servo. Servo can not rotate in circle. (Note: digital servo do not have this problem because it can switch between servo mode and motor mode.) Ordinary DC motor can not give us feedback about rotate angle but servo can do it. Their usage are different too. Ordinary DC motor use a whole circle rotation as power while servo use certain angle of an object it controlled such as robot joint. The servo system can be controlled by impulse, which can change its width. We use control cable to transmit impulse. The parameter of impulse has maximum value, minimum value and frequency. Generally speaking, the cycle of servo reference signal is 20ms and the width is 1.5ms. The position defined by servo reference signal is middle position. Since servo has a maximum rotate angle, the definition of middle position is from this position the maximum value and the minimum value are the same. Most importantly, different servo may have different maximum rotate angle but the impulse width of middle position is the same and that is 1.5ms.   

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-11.jpg)

Note: Micro:bit official has loaded servo control code into bricks.When using Makecode to do program, you don’t have to take some complex information (e.g. the width of impulse) into consideration.

Servo has many categories. However, all of servos have three cables connected externally. These cables usually have three different colors( brown, red, orange ) to differentiate each other. (Different servos brand may have different cable colors.) The brown cable is for connecting GND, red cable is for positive power cable and orange cable is for signal cable.  

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-9.jpg)


## Hardware Connection
---

Please complete hardware connection according to the picture below. 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-4.png )

After connection, you will see: 

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-9.jpg) 

## Programming
---
Open Microsoft Makecode, write your code in the edit area. I would like you to program by yourself first. 

Of course, you can see the whole code directly in the link below. Just click “Edit”on the top right corner of the interface, then click “Download” on the bottom right corner to download your code into micro:bit.

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_Yd7X6x1dKfgv" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

## Code Explanation
---
**Servo Write Pin**
Write a value to the servo on the specified pin and control the shaft.
This function will move the shaft of a standard servo to the specified angle, or set the speed of a continuous rotation servo. (0 specifies full speed in one direction, 180 specifies full speed in the other, and approximately 90 specifies no movement.)

## Experiment Result
We can see the servo rotates with angle range from 0 degree to 180 degree.
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-5.gif)


## Think
---
If we want to use temperature sensor and servo to make a dial thermometer, then how to design circuit and program? We look forward to your comments or further discussion with us.

## Relative Readings
---
- [Micro_bit_Starter_Kit_Lesson_01_LED](/Micro_bit_Starter_Kit_Lesson_01_LED/)
- [Micro_bit_Starter_Kit_Lesson_02_Button](/Micro_bit_Starter_Kit_Lesson_02_Button/)
- [Micro_bit_Starter_Kit_Lesson_03_Trimpot](/Micro_bit_Starter_Kit_Lesson_03_Trimpot/)
- [Micro_bit_Starter_Kit_Lesson_04_Photocell](/Micro_bit_Starter_Kit_Lesson_04_Photocell/)
- [Micro_bit_Starter_Kit_Lesson_05_RGB_LED](/Micro_bit_Starter_Kit_Lesson_05_RGB_LED/)
- [Micro_bit_Starter_Kit_Lesson_06_Self_lock_Switch](/Micro_bit_Starter_Kit_Lesson_06_Self_lock_Switch/)
- [Micro_bit_Starter_Kit_Lesson_07_Temperature_Sensor](/Micro_bit_Starter_Kit_Lesson_07_Temperature_Sensor/)
- [Micro_bit_Starter_Kit_Lesson_08_Servo](/Micro_bit_Starter_Kit_Lesson_08_Servo/)
- [Micro_bit_Starter_Kit_Lesson_09_Buzzer](/Micro_bit_Starter_Kit_Lesson_09_Buzzer/)
- [Micro_bit_Starter_Kit_Lesson_10_Motor](Micro_bit_Starter_Kit_Lesson_10_Motor)
- [Micro_bit_Starter_Kit_Lesson_11_Rainbow_LED](/Micro_bit_Starter_Kit_Lesson_11_Rainbow_LED/)
- [Micro_bit_Starter_Kit_Lesson_12_Accelerometer](/Micro_bit_Starter_Kit_Lesson_12_Accelerometer/)
- [Micro_bit_Starter_Kit_Lesson_13_Compass](/Micro_bit_Starter_Kit_Lesson_13_Compass/)
- [Micro_bit_Starter_Kit_Lesson_14_Ambient_Light](/Micro_bit_Starter_Kit_Lesson_14_Ambient_Light/)

## FAQ
---

   

