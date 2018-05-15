![12](https://i.imgur.com/5RJ1KJn.jpg)   

## Introduction   
---   
Micro:bit has integrated multiple sensors including accelerometer. Today, we are going to use accelerometer to make an level device and display the inclination on NeoPixel ring in bar chart format.    


## Component List  
---
### Hardware:  
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [micro:bit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x 8 RGB LED NeoPixel Ring  
- 1 x [Breadborad Jumper Wire 65pcs Pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  


**Tips: If you want all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html).**  
 

### Software:  
Microsoft Makecode Online Editor  

## Major Component Introduction 
---
**Accelerometer**  
There is an accelerometer on your micro:bit which detects the speed change of micro:bit. It converts analog information into digital form that can be used in micro:bit programs. Output is in milli-g. The device will also detect a small number of standard actions, e.g. shake, tilt and free-fall.  
 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-15.jpg )  

The corresponding X, Y, Z axle direction of accelerometer are showed below:   

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-12.jpg)   


## Hardware Connection  
---
Please complete hardware connection according to the picture below.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-6.png)   

After connection, you will see:  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-12.jpg)    

## Programming  
Open Microsoft Makecode, write your code in the edit area. I would like to suggest you program by yourself first.  

Of course, you can download the whole program from the link below.  

[https://makecode.microbit.org/_R2yHPUecyh2i](https://makecode.microbit.org/_R2yHPUecyh2i)   


## Code Explain  
---
**show bar graph**  
Display the value with bar chart format just similar to plot bar graph.  

**Acceleration**  
Get the acceleration value (milli g-force) in one of three dimensions, or the combined force in all directions (x, y, and z).  


## Experiment Result  
---
With the inclination of micro:bit, LED bead on Neopixel ring gradually illuminated one by one. The bigger inclination angle, more LED beads will be illuminated.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-8.gif)  


## Think  
---
In this case, we have judged the inclination of one direction(X axle) only. If we want to test the inclination of a flat surface( say XY flat surface), then how to design circuit and program. We look forward to your comments and further discussions with us.   

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

   

