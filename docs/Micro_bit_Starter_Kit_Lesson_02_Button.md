![2](https://i.imgur.com/SVbSfPB.jpg)

## Introduction:
---

In lesson 1 , we have learned how to use Micro:bit to control 2 LED beads and make them twinkle alternatively. This time we are going to use a button to control LED flash. That means when we press down the button, 2 LED beads flash in turns; release the button, LED beads stop flashing.


## Components:
---
### Hardware:

- 1 x [Micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)
- 1 x Micro-B USB Cable  
- 1 x [Microbit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)
- 2 x LED
- 2 x 100 Ohm Resistors  
- 1 x Momentary Pushbutton Switch
- 1 x [Breadborad jumper wire 65pcs pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)


**Tips: If you want to buy all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html).**
 
 
### Software:
Microsoft Makecode Online Editor



## Major Components Introduction
---

#### Momentary Pushbutton Switch

This is a common component for controlling electronic devices. It is mostly used to connect or cut off control circuit so that it can achieve motor or other electronic equipment control.
Momentary Pushbutton Switch usually stays open. When it is pressed down, circuit connected; when it is released, it will bounce back to the status of disconnection.

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-4.jpg)

Momentary Pushbutton Switch has 4 footers which can be divided into 2 groups: footer 1 short connected with footer 2, footer 3 short connected with footer 4.

![]( https://www.elecfreaks.com/wp-content/uploads/2018/03/3-4.jpg)


## Hardware Connection
---

Connect your components according to the picture below:

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-1.png) 

After connection, you will see:

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-5.jpg)


## Programming
---

Click to open[Microsoft Makecode](https://makecode.microbit.org/), write your code in the edit area. We would like to suggest you to write code by yourself first.

Of course, you can see the whole program in the link below. Just click the Edit on the right top corner , and then click Download on the right bottom corner to download code into Micro:bit.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_6sjLfwXVhaxg" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>


## Code Explain:
---
**on start**

An event that runs when the program starts.
The on start is a special event that runs when the program starts, before any other event. Use this event to initialize your program.

**set pull**

Configure the electrical pull of the specified pin.
Many micro:bit pins can be configured as pull-ups. For example, a pull-up can set a pin’s voltage to high (3.3 volts, or 1 when calling digital read pin). If one end of a button is connected to P0 (set to high) and the other end is connected to GND (0 volts), then when you press the button, P0 is driven to 0 volts, and the micro:bit software can detect a button press.

**if**

If starts a condition judgement sentence. When the expression behind if is true (or 1), then operate program in than. When the expression behind if is false (or 0), it will jump out of the program circulation. Here is If sentence structure:

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/6-3.jpg)

**digital read**

Digital read to read the voltage of pin. When read out high voltage, it shows 1. When read out low voltage, it presents 0.


## Experiment Result:

When you press down the button, you can see 2 LED beads twinkle by turns; release the button, they stop flashing.
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-1.gif)


## Think
---
If we want to light red LED when press down the button and light green LED when release the button, then how to program? We would like to see your comments or further discussions with us. 

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

   

