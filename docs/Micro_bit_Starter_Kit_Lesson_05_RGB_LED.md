![5](https://i.imgur.com/mEAx3Tx.jpg)  

## Introduction  
---
RGB LED is a kind of LED. It can emit light with three different colors: red, green, and blue. In this experiment, we are trying to make RGB LED gradually shift its light among the three different colors.    

## Component List  
---

### Hardware:  
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [microbit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x RGB LED  
- 3 x 100 Ohm Resistors  
- 1 x [Breadborad jumper wire 65pcs pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  

**Tips: If you want to buy all components above, you may need [Elecfreaks Micro:bit Starter Kit] (http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html) .**  
 
### Software:  
Microsoft Makecode Online Editor  


## Major Component Introduction
---
### RGB LED
RGB LED is a kind of LED, which has integrated red LED, green LED, and blue LED into a component. We all knows that the three primary colors of light are red, green, and blue. With different groups of the three color lights, we can create all colors of the world. Similarly, if we use RGB LED to group lights with different brightness, then it can form various colors.  

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-7.jpg)
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-5.jpg)
  
RGB LED can be divided into 2 types: common anode and common cathode. In common-cathode RGB LED, its common port usually connects GND, while in common-anode RGB LED, its common port connects VCC. In this experiment, we choose common-cathode RGB LED . 

## Hardware Connection
---

Please complete hardware connection according to the picture below.

![]( https://www.elecfreaks.com/wp-content/uploads/2018/03/4-3.png)

After connection, you can see:
  
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-6.jpg)


## Programming
---

Open Microsoft Makecode, write code in edit area. I would like to suggest you program by yourself first. 

Of course, if you want to see the whole program directly, you can click the link below. Just click “Edit”on the right top corner of the interface you opened, then click “Download” on the right bottom to download code into micro:bit directly.

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_7PJd01g8pc8i" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

## Code Explain
---
**Change Value**
Set the value for local and global variables. change r by 1 equals “r=r+1”.

**repeat**
Run part of the program the number of times you say. 

**function**
A function is some amount of code you can reuse in your program. You create a function using a function definition which names the function and has its code. A function call is when you use a function by its name somewhere in your program.

**call function**
Use a function by its name somewhere in a program.

![](https://www.elecfreaks.com/wp-content/uploads/2018/05/6.jpg)

In this experiment, we have set three variables: r、g 、b, which is used to record brightness value of red light, green light, and blue light separately. At the initial status, only red light will be illuminated. 

![](https://www.elecfreaks.com/wp-content/uploads/2018/05/7.jpg)

Then we have to create 3 functions to realize gradual change among the three colors.  
For example, “RtoG” function is for realizing transformation of red light and green light. If we implement the circulation of the function for once, then P0 analog input “-1”( red light brightness decreased a little bit) 
, and P1 analog input “+1” ( green light brightness increased a little bit). After implement circulation for 1023 times, P0 analog input become “0” (red light turned off), and P1 analog input becomes “1023”(green light illuminated). Finally, it has realized gradual change smoothly.

![](https://www.elecfreaks.com/wp-content/uploads/2018/05/8.jpg)

Circulate the three functions to realize color gradual change smoothly.


## Experiment Result
---
Press button A, LED turns red. 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-6.jpg)
Press button B, LED turns green. 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-8.jpg)
Press button A+B, LED turns blue.
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-6.jpg)

## Think
---  
If we want to use RGB LED to emit cyan light, magenta light, yellow light, then how to design circuit and program? We look forward to your comments or further discussions with us. 

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

   

