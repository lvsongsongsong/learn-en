![13](https://i.imgur.com/xMxllOG.jpg)  

## Introduction  
--- 
Do you know compass? I believe most of you have played it ever. Today I am going to use micro:bit to create a compass and display its direction on NeoPixels ring. Want to know how I do it? Just read the article below and follow my steps. Let’s go!  

## Component List  
---
### Hardware:  
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [micro:bit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x 8 RGB Rainbow LED Ring  
- 1 x [Breadborad Jumper Wire 65pcs Pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  

**Tips: If you want all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html).**  

### Software:  
Microsoft Makecode Online Editor  

## Major Component Introduction 
---
**Compass**  
Here, compass in reality is a magnetometer. The magnetometer is a separate chip that provides magnetic field strength sensing. A software algorithm in the standard runtime uses the on board accelerometer to turn these readings into a board orientation independent compass reading. The compass must be calibrated before use, and the calibration process is automatically initiated by the runtime software. This device is connected to the application processor via the I2C bus.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-16.jpg)     

## Hardware Connection  
---
Please complete hardware connection according to the picture below.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-6.png)   

After connection, you will see:  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-11.jpg)   
We have to pay attention we must fix the Rainbow LED Ring according to the direction showed in the picture so that it can point right direction.   


## Programming  
---
Please open Microsoft Makecode, write your code in the edit area. I would like to suggest you program by yourself first.  
Of course, you can download the whole code from the link below.   
[https://makecode.microbit.org/_PKJ3sLasJbK6](https://makecode.microbit.org/_PKJ3sLasJbK6)  

## Code Explain  
---
**Compass Heading**  
Find which direction on a compass the micro:bit is facing.   
The micro:bit measures the compass heading from 0 to 360 degrees with its magnetometer chip. Different numbers mean north, east, south, and west. 0 degree mean the true north.   
NeoPixel ring has 8 LED beads, which can stand for 8 directions: North, North East, East, South East, South, South West, North West.   

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-13.jpg)   

We divide this 360 degree coordinate system into 8 segments in average to help us judge the output value of Compass Heading. When the value comes to a segment, it means at that time micro:bit point at the direction of the segment shows.   

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/6-8.jpg)  
 
The function has set 2 pixel point in a diagonal into red and blue separately while other LED beads closed. We use red color to stand for true north, blue color to show true south and 0 color value of RGB for extinguish the LED bead light.     
Rotate micro:bit, the direction will change. However, we have to make Rainbow LED Ring always point at the same direction. So we must make NeoPixels bead light rotate in the opposite direction. Here, we use rotate pixels to define the offset value of Rainbow LED Ring.  

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/7-8.jpg)   

The key point of this program is to judge the output value of Compass Heading appears in which direction segment and offset the ring color value in the opposite direction. The whole code seems quite long enough, but actually most of it are very similar. It is very simple and easy. You can do it by yourself!  


## Experiment Result  
---
Rotate the whole device, you can see the Rainbow LED Ring always point at the same direction.   
Note: Every time you start to use the compass (for example, if you have just turned the micro:bit on), the micro:bit will start to calibrate compass (adjust itself). It will ask you to draw a circle by tilting the micro:bit.  
If you are calibrating or using the compass near metal, it might confuse the micro:bit.  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-9.gif)  



## Think  
---
If this experiment do not use Rainbow LED Ring but use the arrow displayed on micro:bit as indicator, then how to design circuit and program? We look forward to your comment and further discussion with us.  


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

   

