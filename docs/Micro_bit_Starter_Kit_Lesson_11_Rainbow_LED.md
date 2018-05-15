![11](https://i.imgur.com/F2gbRrO.jpg)    

## Introduction   
---
8 RGB Rainbow LED Ring is based on ws2812b bead. Its biggest characteristic is single IO control and infinite cascade connection. In this experiment, we are going to use micro:bit to drive 8 RGB Rainbow LED Ring and realize rainbow color gradual change.  

## Component List   
---
### Hardware:  
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [micro:bit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x 8 RGB Rainbow LED Ring  
- 1 x [Breadborad Jumper Wire 65pcs Pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  


**Tips: If you want all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html) . **  


### Software:  
Microsoft Makecode Online Editor  

## Major Component Introduction  
---
**8 RGB Rainbow LED Ring**   
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-14.jpg)   
8 RGB Rainbow LED Ring is an LED ring made of 8 ws2812b beads in cascade connection. Ws2812b is an intelligent outer control LED source, which has integrated control circuit and light emitting circuit. It has same appearance with 5050LED bead.   
The digital protocol adopts communication method of single line goes to zero. After pixel point restoration, DIN will receive the data sent from the controller. Once the first 24-bit data received was extracted by the first pixel point, it will be sent to the internal digital lock storage device of pixel point and the rest data amplified through the inner transformation processing circuit will be sent to the next pixel point from DO port.  Every time it passes through a pixel point transmission, the signal will decrease 24bit. The pixel point uses automatic transformation forwarding technique, thus the pixel cascade connection quantity do not limited by signal transmission but the speed of transmission only.  
LED has advantages of low voltage drive, energy-saving and environment protect, wide scattering angle, good consistency, ultra-long life, etc.. To integrate control circuit onto LED, the circuit will become more simple, easier to install and have smaller volume.   


## Hardware Connection  
---
Please complete the hardware connection according to the picture below.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-6.png)  
Note: There are two cables lead out by the ring. One is DI and the other is DO. We should connect DI.  

After connection, we can see:  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-10.jpg)    


## Programming  
---
Open Microsoft Makecode, write your code in the edit area. I would like to suggest you program by yourself.    
In this experiment, we will add a package of code to enable us to use our 8 RGB Rainbow LED Ring. Click on Advanced in the Code Drawer to see more code section and look at the bottom of the Code Drawer for Add Package.  

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-7.gif)  

Of course, you can download the whole code from the link below.  
[https://makecode.microbit.org/_cvrLAKeJC2yT](https://makecode.microbit.org/_cvrLAKeJC2yT)  


## Code Explain  
---
**set to NeoPixel**  
*set to NeoPixel* is used for initialize the bead. Among it, three parameters need to be set: “pin” is set to be the footer connect LED strip, "with x leds" set to be the quantity of bead, and "as RGB" to be the type of bead.  

**show rainbow**  
It is used to make the light of LED strip become rainbow color gradual change.  

**show**  
After we set the color of LED, it will not start to work. To make it works, you have to use *show*.  

**sotate pixels**  
Make LED color move in circle.    

## Experiment Result  
---
We can see the light of 8 RGB Rainbow LED Ring is rotating with rainbow color.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2.gif)  


## Think  
---
Imagine the ring is a big eye, in order to make it twinkle, then how to design circuit and program? We look forward to your comments or further discussion with us.  


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

   

