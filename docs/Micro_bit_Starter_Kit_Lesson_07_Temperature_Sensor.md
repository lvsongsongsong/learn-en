![7](https://i.imgur.com/fMCJitN.jpg)

## Introduction
---
Temperature sensor is a kind of sensor that can feel temperature and transfer it into output data. Temperature sensor is the core component of temperature gauges and instruments. It has multiple categories. In this experiment, we are going to learn analog temperature sensor--TMP36 and display its data on the screen of Micro:bit.

## Components List
---
### Hardware：
- 1 x [micro:bit Board](http://www.elecfreaks.com/estore/bbc-micro-bit-board-for-coding-programming.html)  
- 1 x Micro-B USB Cable  
- 1 x [microbit Breadboard Adapter](http://www.elecfreaks.com/estore/microbit-breadboard-adapter.html)  
- 1 x [Transparent Breadboard - 83 * 55 mm](http://www.elecfreaks.com/estore/transparent-breadboard-83-55-mm.html)  
- 1 x TMP36 Temperature Sensor  
- 1 x [Breadborad Jumper Wire 65pcs Pack](http://www.elecfreaks.com/estore/breadborad-jumper-wire-65pcs-pack.html)  

*Tips: If you want all components above, you may need [Elecfreaks Micro:bit Starter Kit](http://www.elecfreaks.com/estore/elecfreaks-micro-bit-starter-kit-795.html).*
 
### Software:
Microsoft Makecode Online Editor


## Major Components Introduction
---
### TMP36
TMP36 is a kind of analog temperature sensor. Its output voltage and temperature forms a linear relationship. That means higher temperature will have bigger output voltage.

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/2-10.jpg)

**Note:**
When we look at the front side marked “TMP36”, the left footer of the core is VCC, middle is Vout, and the right footer is GND. You can’t connect it wrong or the components connected might be damaged. 

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/3-8.jpg)

Here’s the curve chart for output voltage of TMP36 changing with temperature:

 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/4-7.jpg)
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/5-8.jpg)
 
We can know from the above chart that the temperature formula is:

Temperature（℃）=(Output Voltage（mV）-500)/10


## Hardware Connection
---
Please complete hardware connection according to the picture below.
![]( https://www.elecfreaks.com/wp-content/uploads/2018/03/6-4.png)
After connection, you will see:
 ![](https://www.elecfreaks.com/wp-content/uploads/2018/03/7-6.jpg) 

## Programming
---
Open Microsoft Makecode, write your code in the edit area. I would like to suggest that you program by yourself first.
Of course, you can see the whole program in the link below directly. Just click “Edit” on the top right corner of the interface, then click “Download” on the bottom right corner to download code into Micro:bit directly. 

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_7MLCRdhek0mJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

## Code Explain
---
**map**
Remaps the specified value from one range to another. This function maps the value of **from low** to the value of **to low**, the value of **from high** to the value of **to high**, and intermediate values to intermediate values.
This function does not constrain values to the ranges, because out-of-range values are sometimes intended and useful. If you need to limit a range, you can use the **Math.clamp** function before or after calling this function.
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/8-4.jpg)
 
In our program, we have to use brick **Map** to transfer the read-out analog data into voltage(mV). 
If **analog read** value is 0 to 1023, so **from low** is 0, **from high** is 1023.
The basic voltage of Micro:bit is 3.3V, i.e. 3300Mv. So **to low** is 0, **to high** is 3300.

![](https://www.elecfreaks.com/wp-content/uploads/2018/03/9-2.jpg)
Temperature（℃）=(Output Voltage（mV）-500)/10
Then according to the formula above to calculate temperature value. 


## Experiment Result
micro:bit screen displays the present temperature value. 
![](https://www.elecfreaks.com/wp-content/uploads/2018/03/1-4.gif)


## Think 
---
In this experiment, Micro:bit displays the centigrade temperature. If we want to display the Fahrenheit temperature, then how to design circuit and program? We look forward to your comments or further discussion with us.


## Relative Readings
---
[Start Your Micro:bit Programming Trip](https://www.elecfreaks.com/9299.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 01:LED](https://www.elecfreaks.com/9784.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 02:Button](https://www.elecfreaks.com/9825.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 03:Trimpot](https://www.elecfreaks.com/9879.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 04:Photocell](https://www.elecfreaks.com/9909.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 05:RGB LED](https://www.elecfreaks.com/9978.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 06:Self-lock Switch](https://www.elecfreaks.com/10061.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 08:Servo](https://www.elecfreaks.com/10221.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 09:Buzzer](https://www.elecfreaks.com/10318.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 10:Motor](https://www.elecfreaks.com/10362.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 11:Rainbow](https://www.elecfreaks.com/10508.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 12:Accelerometer](https://www.elecfreaks.com/10529.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 13:Compass](https://www.elecfreaks.com/10567.html)  
[ELECFREAKS Micro:bit Starter Kit Experiment 14:ambient light](https://www.elecfreaks.com/10649.html)  
