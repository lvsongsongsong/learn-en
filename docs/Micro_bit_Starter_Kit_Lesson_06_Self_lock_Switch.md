![6](https://i.imgur.com/ogadD6b.jpg)  

## Introduction
---
Self-lock switch is a kind of common button switch. When we press its button for the first time, the switch is connected and remains that status, which is called “self-lock”. When we press the button for the second time, the switch is disconnected. At the same time, the button will bounce back to its initial place. In this experiment, we are going to use self-lock switch to control LED light.

## Component List
---
### Hardware：
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [microbit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x Self-lock Switch  
- 1 x LED  
- 1 x 100 Ohm Resistors  
- 1 x [Breadborad jumper wire 65pcs pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  

**Tips: If you want all components above, you may need [Elecfreaks micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html).**
 
### Software:
---
Microsoft MakeCode Online Editor


## Major Components Introduction
---
### Self-lock Switch
Self-lock switch normally means switch with built-in mechanical lock function. Press down the switch and then release, it will not fully bounce up because it is locked. You have to press it again, then it will be unlocked and fully bounce up. This is the so-called Self-lock Switch. It is widely used to earlier televisions and monitors with function of directly completely power off.

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-9.jpg)

Note: This kind of self-lock switch contains two groups of double-throw switch. In this experiment, we use a group only. So we cut down the common footer of a group.


## Hardware Connection:
---

Please complete hardware connection according to the picture below.
 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/6-3.png)

After connection, you will see:
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-6.jpg)


## Programming 
---
Please open Microsoft Makecode, write your code in the edit area. I would like to suggest you to program by yourself first.

Of course, you can see the whole program directly in the link below. Just click Edit on the top right corner of the interface to start edit your program. Once you completed edit, click "Download" in the bottom right corner of the interface to download your code directly into Micro:bit..

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_2UHaYkMfpKc6" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>


## Code Explain
---
**set events** 
Configure the type of events emitted by a given pin.

**on events **
Raise an event in the event bus.
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-7.jpg) 

In this case, w designed 2 events: P0 voltage rise and fall. Every time we press down the switch, voltage in P0 port will change for once. When voltage start shifting from 0V to 3.3V, we call it “ Rise”. When voltage start shifting from 3.3V to 0V, we call it “Fall”.

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/6-6.jpg) 

## Experiment Result
---
Press down self-lock switch, LED turned on; press again, LED turned off. 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/未标题1.gif)


## Think
---
Usually stair light use double-throw switch to realize this function. We can  turn on the light of upstairs and turn off the light of downstairs. Vice versa. Suppose if we want to use 2 self-lock switch to realize stair light function, then how to design circuit and program? We look forward to your comments or further discussion with us.

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

   

